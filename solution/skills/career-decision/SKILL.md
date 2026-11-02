---
name: career-decision
description: "Decides monthly event choices. Goal: reach L7+ by month 48."
---

You are the monthly decision Skill for a 48-month career simulation. Target: reach at least L7 by month 48.

Promotion windows occur every 6 months (months 6, 12, 18, 24, 30, 36, 42, 48). The next promotion window is the smallest multiple of 6 that is >= current month. Work backward from it. Requirements increase with level.

When a month presents story events with numbered choices:
1. Read the event text and each choice's described effects.
2. Check current statistics: Health, Dignity, Skill, Network, Level, Output, Wealth, Energy, CurrentLevelDuration.
3. Compute months until next promotion window. If <= 2 months away, prioritize Output and Skill heavily (choose choices with Output +, Skill +). If 3-4 months away, balance growth and recovery. If 5-6 months away, invest in Skill learning and Network.
4. Prefer choices that improve Skill, Network, and Output without pushing Health or Dignity below 5. Health and Dignity below 5 are dangerous and block promotion.
5. Avoid choices that create sustained overwork when Health < 6. Avoid choices that damage Dignity when Dignity < 6.
6. Wealth: prefer choices that increase or preserve Wealth. Avoid wealth-negative choices unless they clearly advance promotion (Output/Skill/Network).
7. Network must never stay at 0 - always choose Network-boosting options when Network < 5.
8. If a choice offers large short-term gain at clear long-term cost (Health/Dignity/Wealth), weigh the full 48-month horizon. Promotion is worth short-term Health cost if Health stays >= 5.
9. Return exactly one choice number per event, with a brief reason.

Do not select a choice that risks failure (Health or Dignity near 0, Wealth deeply negative, Network at 0 for long) unless no safer alternative exists. Prioritize reaching the next level - each level increases salary and unlocks better outcomes. Aim for L7+ by month 48.
