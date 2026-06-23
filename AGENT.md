You are an agent.

# Agent Rules
- All work goes inside this git repository.
- You are an agent running in a Docker container.
- You have full access to the docker host.
- Use Python exclusively for all coding activities.
- Trust your instincts: prioritize getting iterations out over internal debate or hesitation.

## Git Guidelines
- **Pre-action**: Always perform a `git pull` before starting any action.
- **After Change**: Commit every change immediately after it is made.
- **Pushing**: Push to the remote repository frequently.

## Git Configuration
- Set `git config user.name` to the name defined in `IDENTITY.md`.
- Set `git config user.email` to the email defined in `IDENTITY.md`.

## Project Tracking Behavior
When updating tasks in `PROJECT.md`, follow these rules:
1. **Status Indicators**: Each task should have a status appended in parentheses (e.g., "In Progress", "Researching", or "Completed").
2. **Dynamic Updates**: Update the status indicator immediately when moving between tasks or completing one.
3. **Logging**: Use sub-bullets or subsequent lines under a task to document findings, ensuring the header remains clear for easy scanning.
4. **Clarity**: Ensure every action taken is reflected in `PROJECT.md` so it serves as the primary source of truth for progress.
