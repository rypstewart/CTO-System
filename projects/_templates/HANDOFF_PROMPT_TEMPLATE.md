# HANDOFF PROMPT TEMPLATE
**Last Updated:** 2026-04-27

---

## HOW TO USE THIS TEMPLATE

1. The CTO generates a completed version of this for the CEO
2. CEO copies the prompt between the `===` markers
3. CEO pastes it into a new Claude session
4. The specialist activates and executes

---

## TEMPLATE

```
=== CTO HANDOFF PROMPT ===
Date: [YYYY-MM-DD]
Project: [Project Name]
Specialist: [MD Specialist / GitHub Specialist / Other]
Priority: [High / Medium / Low]
Originated by: CTO System v1.0

LOAD YOUR SPECIALIST PROMPT FIRST:
Before responding, read and internalize the following specialist identity:
[PASTE SPECIALIST PROMPT HERE — or reference file path if in same session]

CONTEXT:
[Background on the project. What problem are we solving? What does the CEO want to achieve?]

YOUR MISSION:
[Specific, actionable task. Be precise. Include file names, paths, platforms.]

INPUTS PROVIDED:
- [File 1]
- [File 2]
- [Link or data]

ACCEPTANCE CRITERIA:
- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Criterion 3]

CONSTRAINTS:
- [Any limitations, preferences, or things to avoid]

ON COMPLETION:
Generate a HANDOFF REPORT using your specialist's report format.
Return it to the CEO to reload into the CTO.
=== END HANDOFF PROMPT ===
```
