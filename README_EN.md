# DWMY Review
👉️[English Version](README_EN.md)

## Overview
DWMY Review is a reflection system of the individual, by the individual, for the individual.

DWMY stands for Daily, Weekly, Monthly, and Yearly.

## Concept
- 1: Take notes every day (daily notes)
- 2: Once a day, reflect using your daily note (daily review)
- 3: Once a week, reflect using seven daily notes as input (weekly review)
- 4: Once a month, reflect using 4-5 weekly review results as input (monthly review)
- 5: Once a year, reflect using 12 monthly review results as input (yearly review)

By stacking them up this way, you can keep reflecting at a realistic volume.

Without DWMY, you'd end up trying to recall seven days' worth of details during a weekly review, or re-checking 30 days' worth of details during a monthly review. That would probably be impossible. On the other hand, if you practice DWMY, for a weekly review you only need to look at the seven daily-review outputs, and for a monthly review you only need to look at 4-5 weekly-review outputs. That makes reflection realistically doable.

## ====

## Tools to use
Any of the following should work well.

- Write in plain text using a text editor or IDE
- Write in Cosense or other lightweight wikis/notes that let you create pages freely
    - 🐰If you want to feed it to generative AI, something you can copy and paste as plain text, or export, is better. I recommend Cosense.

## What to write
Daily

- Anything: daily tasks, ideas, work notes, a journal, etc.
- The content of your daily review
- Example filename: `2025-12-31.md`

Weekly

- The daily notes (links to them) included in that week
- The content of your weekly review
- Example filename: `2025-12-w4.md`, `2025-12-28-wr.md`

Monthly

- Links to the weekly review results for the weeks included in that month
- The content of your monthly review
- Example filename: `2025-12.md`, `2025-12-31-mr.md`

Yearly

- Links to the monthly review results for the months included in that year
- The content of your yearly review
- Example filename: `2025.md`, `2025-12-31-yr.md`

## What to do in a review
If you create a template and fill it in mechanically, it's easy to write. Examples:

- YWT: What you did, what you learned, what you'll do next
- KPT: Keep (what you want to continue), Problem (issues), Try (what you'll try next)
- 4Y: What to do, what you did, what went well, what didn't go well

You can also structure it on the assumption that a generative AI will write it for you. Examples:

- [coppai-sta](https://github.com/stakiran/coppai-sta)
    - This is the prompt 🐰 uses (the content goes into `%cb%`)
    - 👉️[For weekly reviews](https://github.com/stakiran/coppai-sta/blob/master/wr_for_stary.md)
    - 👉️[For monthly reviews](https://github.com/stakiran/coppai-sta/blob/master/mr_for_stary.md)

## Format
Here are examples in Markdown.

🐰Whether you split files frequently, or keep everything in one file and separate it with `# heading syntax`, is a matter of preference.

### Daily
Content in list format

```
# 2025-12-31
- ...

# 2025-12-30
- ...

# ...
```

Free-form content

🐰This is easier to write than list format, but the downside is that it's not structured, so it's harder to read later and harder for a generative AI to understand as well. However, it depends on the person, and you can compensate by refining the prompt, so in the end it's a matter of preference.

```
# 2025-12-31
...

# 2025-12-30
...

# ...
```

### Weekly
If you do it on Sunday

```
# 2025-12-28
- [2025-12-21](2025-12-21.md)
- [2025-12-22](2025-12-22.md)
- [2025-12-23](2025-12-23.md)
- [2025-12-24](2025-12-24.md)
- [2025-12-25](2025-12-25.md)
- [2025-12-26](2025-12-26.md)
- [2025-12-27](2025-12-27.md)

(Write your reflection content here)

```

### Monthly
```
# 2025-12
- [2025-12-07](2025-12-07-wr.md)
- [2025-12-14](2025-12-14-wr.md)
- [2025-12-21](2025-12-21-wr.md)
- [2025-12-28](2025-12-28-wr.md)

(Write your reflection content here)
```

### Yearly
```
# 2025
- [2025-01](2025-01.md)
- [2025-02](2025-02.md)
- [2025-03](2025-03.md)
- [2025-04](2025-04.md)
- [2025-05](2025-05.md)
- [2025-06](2025-06.md)
- [2025-07](2025-07.md)
- [2025-08](2025-08.md)
- [2025-09](2025-09.md)
- [2025-10](2025-10.md)
- [2025-11](2025-11.md)
- [2025-12](2025-12.md)

(Write your reflection content here)
```