# AI Daily Brief

A daily digest of meaningful AI news — vetted stories with context from what developers, researchers, and practitioners are actually saying, not just headlines.

## Structure

```
daily-briefs/
  YYYY-MM-DD.md   # one file per day
```

## Daily task (scheduled)

Each day, do the following:

1. **Check** whether today's brief (`daily-briefs/YYYY-MM-DD.md`) already exists in the `main` branch. If it does, skip.
2. **Search the web** for the most significant AI news from the past 24 hours.
3. **Write the brief** following the format below.
4. **Create a branch** named `feature/daily-brief-YYYY-MM-DD` from `main`.
5. **Commit** the file to `daily-briefs/YYYY-MM-DD.md` on that branch.
6. **Push** the branch and open a PR against `main`.

## Brief format

```markdown
# AI Daily Brief — [Month Day, Year]

> A curated summary of what's actually happening in AI today, including what
> developers, researchers, and practitioners are saying — not just the headlines.

---

## 1. [Story title]

**What happened:** factual summary of the event.

**What people are actually saying:**

- Real quote or reaction from a developer, researcher, or practitioner with attribution
- Another reaction — sourced from X, HN, forums, or industry press

**Why it matters:** one paragraph connecting this to broader trends.

**Sources:** [Publication](url) · [Publication](url)

---

## 2. [repeat for each story]

---

*Compiled YYYY-MM-DD. Stories cross-checked across multiple sources.*
```

## What makes a story

Each brief covers 4–6 stories per day, filtered for:
- Actual technical or strategic significance
- Real quotes from practitioners, not just press releases
- Context that connects individual stories to broader trends
- No fluff, repackaged old news, or executive press release quotes
