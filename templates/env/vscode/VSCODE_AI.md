# VSCode AI Development Instructions

## Project Context
This project uses ai-devkit for structured AI-assisted development. Phase documentation is located in `docs/ai/`.

## Documentation Structure
- `docs/ai/requirements/` - Problem understanding and requirements
- `docs/ai/design/` - System architecture and design decisions (include mermaid diagrams)
- `docs/ai/planning/` - Task breakdown and project planning
- `docs/ai/implementation/` - Implementation guides and notes
- `docs/ai/testing/` - Testing strategy and test cases
- `docs/ai/deployment/` - Deployment and infrastructure docs
- `docs/ai/monitoring/` - Monitoring and observability setup

## Code Style & Standards
- Follow the project's established code style and conventions
- Write clear, self-documenting code with meaningful variable names
- Add comments for complex logic or non-obvious decisions

## Development Workflow
- Review phase documentation in `docs/ai/` before implementing features
- Copy the base template (`docs/ai/<phase>/README.md`) before creating feature-specific files
- Keep requirements, design, and implementation docs updated as the project evolves
- Reference the planning doc for task breakdown and priorities
- Copy the testing template before writing feature-specific test plans

## AI Interaction Guidelines
- When implementing features, first check relevant phase documentation
- For new features, start with requirements clarification
- Update phase docs when significant changes or decisions are made

## Testing & Quality
- Write tests alongside implementation
- Follow the testing strategy defined in `docs/ai/testing/`
- Reference the commands in `.vscode/commands/` for structured workflows
- Ensure code passes all tests before considering it complete

## Documentation
- Update phase documentation when requirements or design changes
- Keep inline code comments focused and relevant
- Document architectural decisions and their rationale
- Use mermaid diagrams for any architectural or data-flow visuals (update existing diagrams if needed)
- Record coverage results and outstanding gaps in `docs/ai/testing/`

## Available Commands
This project includes custom command templates in `.vscode/commands/` to assist with:
- `new-requirement` - Complete workflow for adding a new feature from requirements to PR
- `code-review` - Structured local code review against design docs before pushing changes
- `execute-plan` - Walk a feature plan task-by-task with interactive prompts
- `writing-test` - Write unit/integration tests targeting 100% coverage
- `update-planning` - Update planning and task breakdown
- `check-implementation` - Compare implementation with design
- `review-design` - Review system design and architecture
- `review-requirements` - Review and summarize requirements
- `capture-knowledge` - Analyze and explain code with recursive dependency analysis
- `debug` - Debug and troubleshoot issues systematically

Use these command files as prompts to guide your AI assistant (like GitHub Copilot or other VSCode AI extensions) through structured workflows.
