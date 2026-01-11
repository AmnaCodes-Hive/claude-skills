name: "error-explainer"
description: "Translate programming or API error messages into clear explanations with actionable fixes. Use when user shares an error."
version: "1.0.0"
---
Error Explainer Skill
When to Use This Skill
User pastes an error message

User is stuck debugging

User mentions API or runtime errors

Procedure
Classify error: Syntax, runtime, configuration, API

Explain meaning: What the error actually says

Identify common causes: Most likely reasons

Suggest fixes: Ordered from most to least likely

Prevent recurrence: Give one prevention tip

Output Format
Error Meaning: Simple explanation
Likely Causes: Bullet list
Step-by-Step Fix: Ordered actions
Prevention Tip: One best practice

Quality Criteria
No guessing beyond evidence

Fixes must be actionable

Explanations written for beginners

Avoid overwhelming with too many solutions

Example
Input: “Invalid API key · Please run /login”

Output:

Error Meaning: The system cannot authenticate your request.

Likely Causes:

API key missing

Expired key

Step-by-Step Fix:

Run /login

Regenerate API key

Prevention Tip: Store keys in environment variables.

