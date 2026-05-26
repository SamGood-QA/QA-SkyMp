# SMP-SMK-SKILLS_PANEL-001

> **Summary:** Character skills panel functionality
>
> **Example:** *The skills panel opens/closes correctly, level icons are interactive, skill levels can be upgraded, level descriptions change correctly, experience points are spent properly, and the maximum amount of experience points does not exceed the threshold.*

| Field | Value |
| :--- | :--- |
| **Status** | Passed |
| **Severity** | Major |
| **Priority** | P2 (Medium) |
| **Environment** | OS: Windows 11 Pro, Device: Desktop PC |
| **Build/Version** | [1c3b345] |
| **Author** | Aleksei Nikolaev |
| **Date Reported** | 2026.05.26 |

---

## Preconditions
- Build is deployed.
- Test account is available.
- The account has more than 1000 experience points.
- If the character is an old man, more than 1300 experience points are required.

## Steps to Reproduce

| # | Action | Expected Result | Actual Result |
|---| :--- | :--- | :--- |
| 1 | Activate the Aedra altar | Prayer animation is played, and the character skills panel opens | - |
| 2 | Hover the cursor over a skill icon | The icon animation is activated, and the skill description appears | - |
| 3 | Click the skill icon | The icon color changes | - |
| 4 | Click "Learn" | The skill changes color depending on its level. The amount of experience points in the "Experience" field decreases. Memory points decrease. | - |
| 5 | Upgrade skill levels beyond the total "Memory" parameter value | Level upgrade does not occur | - |
| 6 | Click "Reset" | A skill reset warning appears | - |
| 7 | Click "Yes" | Skills are reset. Memory points return to the maximum value. Non-old man: 1000, Old man: 1300 | - |
| 8 | Click "Exit" | The panel closes, and the character can move | - |

## Status
- [x] Pass
- [ ] Fail (Link to Bug Report: [#])
- [ ] Blocked
- [ ] Skipped

## Impact Assessment
- [ ] Critical: System unusable.
- [ ] High: Core functionality broken.
- [ ] Medium: Workaround exists.
- [ ] Low: Minor issue.
- [ ] Frequency: [100% / Often / Rarely / Once]
- [ ] Workaround: [None / describe]

## Attachments

