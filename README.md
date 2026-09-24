<div align="center">

# Omer Hayat

### CS @ NYU Abu Dhabi · ML Systems · Robotics · AWS · Software Engineering · SQL

*building software somewhere between models, systems, and machines.*

<br>

<a href="YOUR_WEBSITE">
  <img src="https://img.shields.io/badge/website-111111?style=for-the-badge&logo=vercel&logoColor=white">
</a>
<a href="YOUR_LINKEDIN">
  <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="YOUR_NEWSLETTER">
  <img src="https://img.shields.io/badge/The_Epoch-2962FF?style=for-the-badge&logo=hashnode&logoColor=white">
</a>

</div>

<br>

<img src="./assets/system-map.svg" width="100%" alt="Omer Hayat system map showing ML, robotics and cloud projects">

<br>

```text
omer@github:~$ whoami

CS student @ NYU Abu Dhabi
ML systems + software + robots

currently obsessed with:
> models that can admit uncertainty
> systems that survive outside notebooks
> making four-file ideas become forty-file repositories
```

## About

I build at the intersection of **machine learning and software systems**.

That usually means I start with a model or an idea and end up thinking about APIs, databases, evaluation, cloud infrastructure, failure handling, deployment, and whatever else is required to make the thing actually work.

Sometimes the software controls a robot.

Sometimes it decides that it **doesn't know**.

Both are more interesting that way.

---

# Selected builds

<table>
<tr>
<td width="50%" valign="top">

## 🧠 RepoTriage

**ML issue intelligence that knows when not to answer.**

Predicts labels for GitHub issues, retrieves similar historical issues, estimates confidence, and routes uncertain predictions toward human review.

`ML` `FastAPI` `React` `PostgreSQL`

**R@10:** 0.942 on the held-out retrieval set

→ [Repository](https://github.com/OmerNYU/repotriage)

</td>

<td width="50%" valign="top">

## ☁️ PitchMirror

**An AWS-native ML system for pitch coaching.**

Video enters through S3, asynchronous analysis runs through Step Functions and ECS, and the resulting signals and model outputs are assembled into structured coaching feedback.

`AWS` `ML` `Next.js` `S3` `ECS` `Step Functions`

The interesting problem wasn't just inference. It was everything around it.

→ [Repository](https://github.com/OmerNYU/PitchMirror)

</td>
</tr>

<tr>
<td width="50%" valign="top">

## 🧪 FailSpec

**Bug report → executable evidence.**

Inspects a codebase, forms a reproduction hypothesis, generates a constrained Playwright regression test, executes it, and returns evidence rather than an AI guess.

`TypeScript` `Playwright` `Codex`

→ [Repository](https://github.com/OmerNYU/FailSpec)

</td>

<td width="50%" valign="top">

## ⚽ MatchLens

**Football prediction where time actually matters.**

Premier League modelling with chronological evaluation, leakage guards, rolling pre-match features, walk-forward backtesting, and an unreasonable amount of effort spent making draws behave.

`Python` `scikit-learn` `pandas`

→ [Repository](https://github.com/OmerNYU/Match-Lens)

</td>
</tr>
</table>

---

## Other experiments

**🔥 [Kaboom](https://github.com/OmerNYU/Kaboom_Diffusion)**
A dependency-light C++ fireball renderer built with signed distance fields, ray marching, procedural noise, and questionable numbers of pixels.

**🔎 [Internship Monitor](https://github.com/OmerNYU/Internship-Monitor)**
A stateful internship discovery engine with structured-source monitoring, deterministic eligibility analysis, persistence, retries, and explainable alerts.

---

# Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=py,cpp,ts,js,r,postgres,pytorch,tensorflow,sklearn&theme=dark" />

<br>

<img src="https://skillicons.dev/icons?i=aws,docker,linux,fastapi,nextjs,react,nodejs,git,githubactions,ros&theme=dark" />

</div>

<br>

```sql
SELECT *
FROM interests
WHERE topic IN (
    'ml systems',
    'robotics',
    'cloud',
    'software engineering',
    'data'
)
ORDER BY curiosity DESC;
```

---

# The Epoch

I occasionally turn things I've learned the difficult way into things other people can read the easy way.

**Backpropagation from First Principles**
Neural-network training without treating autodiff as magic.

**Why Machine Learning Models Should Be Allowed to Say "I Don't Know"**
Confidence, calibration, abstention, selective prediction, and human review.

→ **[Read The Epoch](YOUR_NEWSLETTER)**

---

<div align="center">

<sub>most repositories begin with "this should be pretty quick"</sub>

</div>
