# SMP-TC-SKILLS_PANEL_LVL_UP-001

## Metadata
* **Title**: Implemented skill level upgrade
* **Priority**: High
* **Created By**: Aleksei Nikolaev
* **Date**: 2026.05.26

## Objective
Verify that implemented character skills can be upgraded to the maximum level.

## Preconditions
1. The character is a Nord.
2. Experience points are no less than 870.

## Test Data

* Test account
* All skills are at the "Novice" level

## Steps

| # | Action | Expected Result | Actual Result |
|---| :--- | :--- | :--- |
| 1 | Activate the Aedra altar | The prayer animation starts. The character becomes locked. The skills panel opens. Racial discounts are applied. | - |
| 2 | Hover over the "Illusion Mage" skill icon | The icon animation is played, and the skill description appears. | - |
| 3 | Click the icon | The icon color changes. The skill description changes to "Apprentice". | - |
| 4 | Click "Learn" | The character's skill level increases. Experience and memory points decrease considering the racial discount. | - |
| 5 | Hover over the "Illusion Mage" skill icon | The icon animation is played, and the skill description appears. | - |
| 6 | Click the icon | The icon color changes. The skill description changes to "Adept". | - |
| 7 | Click "Learn" | The character's skill level increases. Experience and memory points decrease considering the racial discount. | - |
| 8 | Hover over the "Illusion Mage" skill icon | The icon animation is played, and the skill description appears. | - |
| 9 | Click the icon | The icon color changes. The skill description changes to "Expert". | - |
| 10 | Click "Learn" | The character's skill level increases. Experience and memory points decrease considering the racial discount. | - |
| 11 | Hover over the "Illusion Mage" skill icon | The icon animation is played, and the skill description appears. | - |
| 12 | Click the icon | The icon color changes. The skill description changes to "Master". | - |
| 13 | Click "Learn" | The character's skill level increases. Experience and memory points decrease considering the racial discount. | - |
| 14 | Hover over the "Illusion Mage" skill icon | The icon animation is played, and the skill description appears. | - |
| 15 | Click the icon | Nothing happens. | - |

## Status

- [x] Pass
- [ ] Fail (Link to Bug Report: [#])
- [ ] Blocked
- [ ] Skipped

## Environment
* **Environment**: Windows 11 Pro, Device: Desktop

## Attachments
