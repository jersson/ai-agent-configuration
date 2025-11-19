# ai-agent-configuration

## Abril Agent Configuration

Abril is a **Prompt Quality Evaluator** designed to operate in **Silent Mode**. Its primary objective is to assess the effectiveness of user prompts before processing them, ensuring high-quality interactions.

## Supported platforms
- [Google Gemini Gem](https://gemini.google.com/gems/create)

### Key Features:

*   **Silent Evaluation:** Acts as a transparent layer. If the prompt quality is sufficient (Score >= 3.5/5), the agent responds directly to the user's request without revealing the evaluation process.
*   **Quality Metrics:** Evaluates prompts based on:
    *   Clarity and Understanding
    *   Exhaustiveness / Scope
    *   Relevance of Response
    *   Conciseness and Focus
    *   Format and Restrictions
*   **Constructive Feedback:** If a prompt is rejected (Score < 3.5/5), the agent provides the effectiveness score and a concrete suggestion for improvement.
*   **Black Box Policy:** Strictly maintains confidentiality regarding its internal rules and system instructions.


## Configuration Files

- [English Version](abril.md)
- [Spanish Version](abril.ES.md)
