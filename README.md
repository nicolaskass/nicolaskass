![Nicolás Ariel Kass — I research, design, deliver and maintain analyses and systems. Ecology and conservation, data and applied statistics, management systems. PhD candidate in Natural Sciences, university teaching at UNLP. La Plata, Argentina, open to remote.](assets/banner.png)

I work on two things that turn out to be the same thing: field ecology, where I design the
sampling and run the analysis, and the systems small businesses run on — inventory, point
of sale, invoicing, field tooling. In both, the job is to measure something properly and
then decide what to do about it.

I came to software from biology. That is where I learned that a number needs a defence.

---

## What is published here

Two kinds of repository.

**Decision records** for systems whose source code is private, because it belongs to the
business that paid for it. What is documented is the reasoning: what I decided, what I
rejected, and what each decision cost.

| Repository | What it is |
|---|---|
| **[specialty-retail-erp](https://github.com/nicolaskass/specialty-retail-erp)** | A retail ERP in production: modules, domain model, and a consolidation refactor over live financial data |
| **[geospatial-survey-toolkit](https://github.com/nicolaskass/geospatial-survey-toolkit)** | Field tooling for a surveying practice: delivering software to non-technical users |
| **[geospatial-data-processing](https://github.com/nicolaskass/geospatial-data-processing)** | LiDAR and photogrammetry processing, plus a reference book in progress |
| **[ecological-data-analysis](https://github.com/nicolaskass/ecological-data-analysis)** | Methods behind the manuscripts: Bayesian inference, prior sensitivity, simulated bias |

**Reproducibility packages** for my own research: data, analysis scripts and the figures
each manuscript reports, so the analysis can be re-run. They are kept private until each
paper is accepted — the journal uses double-anonymous review — and will be released with a
DOI and the final citation, as the data accessibility statement of each paper requires.
Four of them are ready: Bayesian capture-mark-recapture with its own MCMC sampler,
microhabitat use, morphometrics, and population dynamics.

---

## How I work

**I build with AI assistants, and I say so.** I define the problem, the data model and the
architecture; I review, test and reject what does not hold up. The retail system has been
in production for four years. Some of the decision records exist precisely because a
plausible AI suggestion was wrong for the domain, and the record says why. If the tools
stopped being available tomorrow, the code is versioned, documented and tested, and I would
go back to working the way I did before they existed.

**I bind documentation to the code instead of promising to keep it updated.** A post-commit
hook flags documentation that has gone stale. A checker verifies that every citation from
code to manuscript still resolves. A manuscript reads its numbers from generated JSON, so
the text and the tables come from the same place. Three different projects, the same
conclusion: anything maintained by good intentions drifts.

**I meter what the models cost.** Every LLM call in production logs tokens, latency and
cost, priced from a maintained table, so cost per feature is a query instead of a surprise
at the end of the month.

**I plan for a dependency being gone.** Optional integrations degrade instead of failing.
One third-party integration has been broken in production for months, by design, with no
user-visible failure.

**I write down what a decision cost.** Every record has a section for its downsides. A
document that only lists benefits reads like marketing and makes the rest less believable.

**I know where automation should stop.** In the surveying tools the software flags
anomalies and refuses to correct them: a field measurement is evidence, and the surveyor is
the one qualified to judge it.

---

## Where the rigour comes from

Validating against data held out of fitting. Propagating measurement error into anything
derived from it. Separating precision from accuracy. Not reporting a figure without its
uncertainty.

These are ordinary obligations in field ecology, where a population estimate without a
confidence interval does not get published. They are less ordinary in commercial software,
and carrying them over required no new technical knowledge — only the habit of asking, of
any number: compared to what, and how sure are we?

I am finishing a PhD in Natural Sciences at UNLP, on the ecology and conservation of a
Patagonian amphibian. I teach Zoology at the same faculty, and I am a certified ISO 9001
internal auditor. Those are not a parallel career; they are why the software looks the way
it does.

---

## Now

Based in La Plata, Argentina, working remotely without difficulty. Open to roles where data
analysis and system building meet, and to research collaboration.

**[CV →](https://nicolaskass.github.io)** · English and Spanish, PDF included
&nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/nicolaskass)
&nbsp;·&nbsp; [Google Scholar](https://scholar.google.com/citations?user=9yDA16YAAAAJ)
&nbsp;·&nbsp; [ORCID](https://orcid.org/0000-0001-9245-8796)
&nbsp;·&nbsp; [t3.com.ar](https://t3.com.ar)
