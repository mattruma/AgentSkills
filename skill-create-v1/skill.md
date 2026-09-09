---
name: skill-create-v1
description: Use this skill when the user wants to create a skill.md. Creates a simple skill.md file using the example template format.
---

When this skill is activated:

1. Create `skill.md`.
2. Always start with a name and description based on a skill.md template.
3. Fill it with the template below.
4. Replace the bracketed placeholders.
5. If details are missing, leave placeholders instead of inventing extra content.
6. Create a downloadable link.

## Guidelines

- Keep the structure simple.
- Use only the sections shown in the template unless the user asks for more.
- Keep the wording short and concise.
- Match the example format closely.

## Examples

Write this exact structure:

```md
---
name: [newly-created-skill]
description: [Write one sentence describing when to use this skill. Write one sentence on what this skill does.]
---
When this skill is activated:

1. [First step or action the agent should take]
2. [Second step or action]

## Guidelines

- [Key guideline or constraint]
- [Another important consideration]

## Examples

**Example 1: [Scenario name]**
- User request: "[Example user input]"
- Expected behavior: [How the agent should respond]

## Notes
[Any additional context, edge cases, or important information the agent should know.]

```

## Notes

Use this when the user wants to create a skill. Always create a downloadable skill.
