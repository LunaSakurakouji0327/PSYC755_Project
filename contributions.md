# Contributions

**Group:** Communication Apprehension Research Team
**Group Members:** Chao Ding, Jiangran Gu, Peiqi Li, Yuhao Wang, Jingyi Zhou
**Project:** Communication Apprehension and Transportation Use: A Group Synthesis of Five Research Memos
**Repository:** https://github.com/LunaSakurakouji0327/PSYC755_Project

---

## How to use this file

Each member of the group completes one section below. Fill in every bullet. Delete the
instructions in *italics* as you go, and delete any unused student sections at the bottom
if your group has fewer than five members.

Three rules:

1. **Components are not co-owned.** No two students may not claim the same component. If you and a partner pair-programmed something, decide who owned it and ackowledge the two person effort. Each person needs their own entry below.
2. **Everything here must be checkable.** We will follow your file paths and click your links. A claim we cannot verify does not count.
3. **Link to permanent URLs, not moving ones.** See the note on line numbers below.

> **Reminder — Markdown link syntax.** Write links as `[link text](https://example.com)`. The visible words go in the square brackets and the URL goes in the parentheses, with no space between the two. For example, `[Permalink to load.py](https://github.com/...)` renders as [Permalink to load.py](https://github.com/...). Bare URLs work too, but named links are easier to read.

### A note on line numbers and links

Line numbers go stale the moment someone edits the file above yours. So do links to a branch. Use GitHub **permalinks**, which pin to a specific commit and never move:

> Open the file on GitHub → click the line number (or drag to select a range) → press **`y`** to convert the URL to a permalink → copy.

A permalink looks like this. Note the 40-character commit SHA in the path:

```
https://github.com/ORG/REPO/blob/a3f2c1e9d4b7.../analysis/model.qmd#L112-L168
```

Not like this (this one rots):

```
https://github.com/ORG/REPO/blob/main/analysis/model.qmd#L112-L168
```

### The data science process

The last bullet in each section asks which portion of the data science process your work contributes to. Name the stage and be specific about your part in it ("data acquisitionand ingestion," "cleaning and validation," "exploratory analysis," "modeling," "evaluation," "visualization and communication," "infrastructure and reproducibility.") If your component spans two stages, say so, and say which one it mostly lives in.

---

## Student 1: Chao Ding (`cding56`)

- **The component I "owned" and that I summarize here is best described as** the transportation mode prediction analysis — comparing communication apprehension's predictive accuracy for public transit use versus ride-share use using simple linear regression models and RMSE comparison.
- **You can find this contribution in a file called** `group_memo/Chao_memo.qmd` **at lines** 1–181. [Permalink to Chao_memo.qmd](https://github.com/[ORG]/[REPO]/blob/[COMMIT]/group_memo/Chao_memo.qmd#L1-L181)
- **Owning this component means** I designed the research question comparing RMSE between public transit and ride-share prediction models; I implemented the data cleaning and recoding of the 12 PRCA items to a 1–5 scale with reverse-scoring; I built the two simple linear regression models; I created the RMSE comparison visualization; and I wrote the interpretation of results showing ride-share use as more predictable. I did not collect the original data — that was provided through the Qualtrics export.
- **The commits or PRs that are most relevant are** [add relevant commit/PR links]
- **The portion of the data science process that this effort contributes to is** stage 5, **Select + Apply** — selecting linear regression as the modeling approach and applying it to compare prediction accuracy across transportation modes. It also contributes to stage 6, **Check + Recheck** — using RMSE as an evaluation metric to determine which outcome is more accurately predicted by communication apprehension.

---

## Student 2: Jiangran Gu (`LunaSakurakouji0327`)

- **The component I "owned" and that I summarize here is best described as** the driver's license status analysis — investigating whether holding a driver's license predicts communication apprehension using independent-samples t-test and boxplot visualization.
- **You can find this contribution in a file called** `group_memo/Research_Memo_License_CA_2.qmd` **at lines** 1–160. [Permalink to Research_Memo_License_CA_2.qmd](https://github.com/[ORG]/[REPO]/blob/[COMMIT]/group_memo/Research_Memo_License_CA_2.qmd#L1-L160)
- **Owning this component means** I formulated the research question about driver's license status and CA; I implemented the reverse-scoring scheme for PRCA items (Q1, Q3, Q5, Q13, Q15, Q18); I calculated the composite CA_total score; I performed the independent-samples t-test with Levene's test for equal variances; I created the boxplot visualization comparing CA scores by license status; and I interpreted the null finding while noting the reverse-scoring scheme's impact on results.
- **The commits or PRs that are most relevant are** [add relevant commit/PR links]
- **The portion of the data science process that this effort contributes to is** stage 5, **Select + Apply** — selecting t-test as the appropriate statistical test for comparing group means, and stage 6, **Check + Recheck** — using Levene's test to verify assumptions and Cohen's d to assess effect size.

---

## Student 3: Peiqi Li (`Peiqili196`)

- **The component I "owned" and that I summarize here is best described as** the visualization strategy analysis — creating scatterplots with fitted linear trend lines to illustrate the relationship between communication apprehension and transportation use across three outcomes (public transportation, ride-share, and overall transportation use).
- **You can find this contribution in a file called** `group_memo/Peiqi_memo.qmd` **at lines** 1–258. [Permalink to Peiqi_memo.qmd](https://github.com/[ORG]/[REPO]/blob/[COMMIT]/group_memo/Peiqi_memo.qmd#L1-L258)
- **Owning this component means** I designed the visual strategy using scatterplots with trend lines; I computed the mean communication-apprehension score across 12 items with appropriate reverse-coding; I combined transportation frequency and rides-per-day items into three composite outcomes; I created three scatterplots with fitted linear trend lines; and I evaluated the effectiveness of this visualization approach for showing weak negative associations. I noted the descriptive nature of conclusions and suggested nonparametric methods as next steps.
- **The commits or PRs that are most relevant are** [add relevant commit/PR links]
- **The portion of the data science process that this effort contributes to is** stage 7, **Visualization and Communication** — designing and implementing effective visualizations to communicate relationships between variables, with a focus on making the overall direction of relationships immediately visible while conveying data variability.

---

## Student 4: Yuhao Wang (`yuhaowang2025`)

- **The component I "owned" and that I summarize here is best described as** the model comparison analysis — comparing three nested regression models (total CA, CA subscales, and interaction term) for predicting public transportation use frequency using RMSE and R² evaluation metrics.
- **You can find this contribution in a file called** `group_memo/memo_yuhao.qmd` **at lines** 1–259. [Permalink to memo_yuhao.qmd](https://github.com/[ORG]/[REPO]/blob/[COMMIT]/group_memo/memo_yuhao.qmd#L1-L259)
- **Owning this component means** I designed the three nested model specifications; I calculated CA_group and CA_interpersonal subscale scores; I implemented the model comparison using RMSE and R²; I created the RMSE comparison visualization; and I interpreted the results showing Model 3 as best-performing but with minimal improvement over simpler models. I also contributed to the main manuscript integration and coordinated the overall project structure.
- **The commits or PRs that are most relevant are** [add relevant commit/PR links]
- **The portion of the data science process that this effort contributes to is** stage 5, **Select + Apply** — selecting and comparing multiple model specifications, and stage 6, **Check + Recheck** — using RMSE and R² as evaluation metrics to determine optimal model complexity and assess predictive performance.

---

## Student 5: Jingyi Zhou (`JingyiZ-Created`)

- **The component I "owned" and that I summarize here is best described as** the cross-cultural analysis — investigating how communication apprehension and public transportation/ride-share use differ by country of residence using violin plots with embedded box plots.
- **You can find this contribution in a file called** `group_memo/CAandPTRSdifferbyCountry.qmd` **at lines** 1–223. [Permalink to CAandPTRSdifferbyCountry.qmd](https://github.com/[ORG]/[REPO]/blob/[COMMIT]/group_memo/CAandPTRSdifferbyCountry.qmd#L1-L223)
- **Owning this component means** I designed the cross-cultural research question; I concatenated and merged multiple data files (FileA, FileB, FileC) by matching Prolific IDs; I implemented the coding of PRCA items on a 1–5 agreement scale with appropriate reverse-coding; I calculated composite CA and PTRS scores; I created violin plots with embedded box plots to visualize distributions across countries; and I focused the analysis on the four largest-sample countries (United States, United Kingdom, Ireland, Canada) for clearer interpretation.
- **The commits or PRs that are most relevant are** [add relevant commit/PR links]
- **The portion of the data science process that this effort contributes to is** stage 4, **Exploratory Analysis** — exploring patterns across categorical groups (countries), and stage 7, **Visualization and Communication** — using violin plots to effectively communicate distributional differences across groups.

---

## Group sign-off

By adding your name below, each member affirms that the account of their own contribution is accurate, and that they have read the other four sections and believe them to be accurate as well.

- [ ] Chao Ding (`cding56`) — 2026.08.05
- [ ] Jiangran Gu (`LunaSakurakouji0327`)— 2026.08.05
- [ ] Peiqi Li (`Peiqili196`)— 2026.08.05
- [ ] Yuhao Wang (`yuhaowang2025`)— 2026.08.05
- [ ] Jingyi Zhou (`JingyiZ-Created`) — 2026.08.05
