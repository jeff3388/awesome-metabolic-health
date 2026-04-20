# White-Hat Promotion Strategy

> Internal reference document — not for the public repo.
> This outlines natural community sharing approaches that do NOT violate Reddit/GitHub/Google spam policies.

---

## Core Principle

**Never post with a promotional intent. Post because the resource genuinely helps the community.**

Every promotion action should pass this test: "If my site didn't exist, would I still share this link for the community's benefit?" If yes, proceed.

---

## Phase 1 — Launch (Week 1–2)

### GitHub Actions

1. **Submit to `sindresorhus/awesome`** (the main awesome list index)
   - [Submission criteria](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md)
   - Requires: 30+ items, CI checks passing, unique content
   - Expected outcome: Verified badge + discoverability from the awesome.re index

2. **Add relevant GitHub topics** to the repo:
   ```
   awesome-list, health, nutrition, weight-loss, bmi, tdee, metabolic-health,
   evidence-based, taiwan, traditional-chinese, intermittent-fasting, mediterranean-diet
   ```

3. **Submit to health-related awesome lists** as a related repo:
   - `awesome-healthcare` — open a PR adding this to their "Awesome Lists" section
   - `awesome-public-datasets` — add the `/data/*.json` files as Taiwan health standards

### Initial Social Presence

- Post on **LinkedIn** (personal/brand page):
  > "We built a curated list of the most important research papers for metabolic health — BMI standards, TDEE formulas, IF studies, supplement evidence grades. Open-source and free. [link]"
  > Target: health professionals, dietitians, sports science academics

---

## Phase 2 — Community Participation (Month 1–2)

### Reddit Strategy

**Rule**: Only post in subreddits where you have genuine participation history. Do not post immediately after account creation.

| Subreddit | Post Type | Suggested Post |
|-----------|-----------|----------------|
| r/loseit (1.6M) | Resource share | "Built an open-source list of evidence-graded supplements — because the marketing claims vs actual research is embarrassing. Feel free to use/share." |
| r/nutrition (1.3M) | Discussion | Reference specific papers from the list in existing discussions; mention the repo organically |
| r/intermittentfasting (800K) | Resource | "Here's a summary of every major IF meta-analysis, with evidence grades." |
| r/fitness (8M) | New comments | Answer questions about supplements, cite the evidence grade table |
| r/longevity (450K) | Resource | Share the longevity/metabolic biomarkers section |
| r/taiwan (健康相關討論) | Taiwan section | Share the 台灣專區 section: "Made a list of Taiwan MoHW health standards in machine-readable JSON" |

**Key rules**:
- Read and follow each subreddit's self-promotion rules
- Never cross-post the same content to multiple subreddits on the same day
- Respond to every comment; genuine engagement is the signal

### Hacker News

**Best post type**: "Show HN: Open dataset of Taiwan health standards in JSON (BMI, TDEE, DRIs)"

The `/data/*.json` files are the strongest HN-worthy asset — developers and data scientists value machine-readable standards that are otherwise only available as PDF government documents.

---

## Phase 3 — Long-Term Authority Building (Month 2–6)

### Backlink Opportunities

1. **Taiwan academic institutions**: Email health science departments at NTU, NTHU, NYCU with a note that the data files might be useful for students; ask if they'd link to it as a resource.

2. **Open-source health projects**: Find projects on GitHub that implement BMI or TDEE calculators and open issues/PRs suggesting they reference the data files.

3. **Wikipedia**: Improve Taiwan BMI standards section in Wikipedia's "BMI" article, citing this repo as a reference for the structured data.

4. **Dietitian blogs**: Reach out to RD bloggers in Taiwan and internationally who write about evidence-based nutrition; offer the supplement evidence grades as a freely usable resource.

### Content Updates That Naturally Attract Links

Schedule quarterly reviews:
- Update supplement grades when new meta-analyses are published
- Add new JISSN position stands as they come out
- Translate key sections to Traditional Chinese for Taiwan academic community

---

## What NOT To Do

- Do NOT use the GitHub repo as a link farm pointing to the main site
- Do NOT create multiple similar repos for different health topics in rapid succession
- Do NOT stuff keywords into the README in unnatural ways
- Do NOT pay for "GitHub star" services or bot followers
- Do NOT post the same link in multiple Reddit posts within 30 days
- Do NOT add the main website URL multiple times in the README — one natural mention in the Taiwan resources section is sufficient

---

## Connecting to the Main Site (燃脂研究所)

Main site domain: **metabolab.tw**

1. Taiwan Resources section already links to metabolab.tw calculators (BMI, TDEE, 211 plate planner)
2. The connection reads naturally — one mention per tool, not repeated across sections
3. Keep it as ONE mention — not every section

The repo independently builds trust and authority. The main site benefits from the trust transfer, but the repo must stand on its own merit.

---

## KPIs to Track (3-month targets)

| Metric | Target |
|--------|--------|
| GitHub Stars | 100+ |
| Forks | 20+ |
| Referenced in other GitHub repos | 5+ |
| Reddit engagement (upvotes across posts) | 500+ |
| Inbound links to main site from this repo | Natural; don't force |
| Awesome-list verified badge | ✓ |
