# Innovation memo: LLaVA Vision Question Ops

        ## Research anchor

        - Paper: Visual Instruction Tuning
        - Score: 9.76/10
        - Official repo: https://github.com/haotian-liu/LLaVA

        ## What this project does differently

        - Wrap the upstream multimodal ai capability in a reviewable operator workflow instead of a single demo script.
- Surface latency, quality, and execution traces so the system feels deployment-ready rather than experimental.
- Design a distinct UI and reporting layer that makes the project portfolio-friendly and easier to explain.

        ## What the upstream code showed

        - No obvious tests directory or test files detected.
- No GitHub Actions workflow detected for repeatable checks.
- No container packaging signal detected, which makes demos and deployment less portable.
- Mixed filename conventions detected: PascalCase, kebab-case, snake_case.

        ## Why the difference matters

        - It makes the original idea easier to explain to operators, hiring managers, and stakeholders.
        - It moves the work from a research or notebook framing into a product and deployment framing.
        - It produces stronger portfolio evidence because the system includes UI, docs, API behavior, screenshots, and clear business outcomes.

        ## Easier production path

        - Keep the first version lightweight and easy to run locally.
        - Preserve a visible API surface, health endpoint, and operator workflow.
        - Package evaluation, screenshots, and runbooks alongside the model or LLM logic.
