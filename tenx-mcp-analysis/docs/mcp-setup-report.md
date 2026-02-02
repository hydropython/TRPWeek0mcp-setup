# Tenx MCP Setup Challenge - Documentation

## Task 2: Rules File Configuration

### What I Did
- Created `.github/copilot-instructions.md` to guide AI agent behavior.
- Structured the rules to cover:
  - Agent identity and purpose
  - Step-by-step reasoning before taking actions
  - Coding style and best practices
  - Interaction rules (how to suggest and explain changes)
  - Error handling and safety
  - Testing and validation steps
  - Communication protocols
  - Debugging steps and troubleshooting behavior
  - Learning and adaptation from past interactions
- Researched best practices inspired by Boris Cherny and other AI agent workflows.

### What Worked
- Rules clearly guided the agent to:
  - Provide explanations before making code changes
  - Suggest multiple approaches with pros and cons
  - Ask clarifying questions when the task was ambiguous
  - Break down complex tasks into smaller steps

### What Didn't Work
- MCP server connection was not active initially due to VS Code update issues.
- Could not test the live agent behavior fully until the Copilot Chat extension was updated.
- Some trial-and-error was required to format the JSON/Markdown properly for the agent to read.

### Insights Gained
- A well-structured rules file dramatically changes how the AI agent responds.
- Explicit instructions and step decomposition help the agent align with my intent.
- Including safety checks and testing steps prevents errors and improves reliability.
- Documenting rules and behavior is essential for reproducibility and evaluation.

## Next Steps
- Test the rules file with an active MCP server once VS Code and Copilot Chat are updated.
- Iterate on rules based on observed behavior.
- Record logs from Tenx MCP server to further refine the agent instructions.

