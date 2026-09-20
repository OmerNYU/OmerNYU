<div align="center">

# Omer Hayat

### CS @ NYU Abu Dhabi · ML Systems · Robotics · Software Engineering · SQL

*I like building systems that know when they're uncertain, software that leaves evidence behind, and occasionally robots that need to understand English.*

<br>

<a href="https://omerhayat-portfolio.vercel.app/">
  <img src="https://img.shields.io/badge/Personal%20Website-000000?style=for-the-badge&logo=vercel&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/omer-hayat-974678204/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="https://omerhayat.hashnode.dev/">
  <img src="https://img.shields.io/badge/The%20Epoch-2962FF?style=for-the-badge&logo=hashnode&logoColor=white">
</a>

</div>

---

```text
$ whoami

Omer Hayat
CS student, ML systems enthusiast, occasional robot whisperer.

$ currently

making models say "I don't know"
teaching a quadruped to understand language
turning side-project ideas into suspiciously large repositories
trying not to introduce data leakage
```

---

## 👋 A little about me

I'm a Computer Science student at **NYU Abu Dhabi** interested in the point where machine learning stops being a model in a notebook and becomes an actual system.

Most of my work ends up somewhere around **ML engineering, full-stack systems, cloud infrastructure, robotics, and data-intensive software**.

I'm especially interested in:

* uncertainty and confidence in ML systems
* evaluation that actually reflects real-world behaviour
* human-in-the-loop systems
* software reliability and failure modes
* data, SQL, and systems that have to maintain state correctly
* building the infrastructure around models, not just the models themselves

Right now, I'm working on language-guided robotics research with a **Unitree Go2**, building ML and software projects, and writing about things I learn along the way.

---

## ⚡ Currently

🤖 **Robotics + VLA research**
Working on language-guided navigation and learned policies for a Unitree Go2 at NYUAD's iCAS Lab.

🧠 **ML systems**
Exploring confidence, abstention, retrieval, evaluation, and human-in-the-loop workflows.

🏗️ **Software systems**
Building APIs, async pipelines, data systems, testing infrastructure, and deployment workflows.

📊 **Data + SQL**
Thinking about how data is stored, queried, validated, moved, and eventually turned into useful decisions.

✍️ **Technical writing**
Writing about ML and systems concepts from first principles through **[The Epoch](https://omerhayat.hashnode.dev/)**.

---

# Things I've built

## 🧠 [RepoTriage](https://github.com/OmerNYU/repotriage)

**Issue intelligence for open-source maintainers.**

RepoTriage predicts GitHub issue labels, retrieves similar historical issues, and deliberately **abstains when confidence is too low** instead of pretending every prediction is trustworthy.

`Python` `scikit-learn` `FastAPI` `React` `PostgreSQL` `Docker`

**Interesting bit:** prediction, confidence-aware abstention, retrieval, and maintainer feedback all live inside one review loop.

---

## 🧪 [FailSpec](https://github.com/OmerNYU/FailSpec)

**Turns bug reports into reproducible regression evidence.**

FailSpec inspects a trusted local React or Next.js repository, forms a reproduction hypothesis, generates a constrained Playwright test, executes it, and returns an evidence-backed verdict.

`TypeScript` `Playwright` `Codex` `React`

**Interesting bit:** the output isn't *"AI thinks this is a bug."*
It's executable evidence.

---

## 🎙️ [PitchMirror](https://github.com/OmerNYU/PitchMirror)

**An AI-assisted pitch coaching system.**

PitchMirror processes recorded pitches through an asynchronous cloud pipeline and turns media, transcript, and model outputs into structured coaching reports.

`TypeScript` `Next.js` `AWS` `Step Functions` `S3` `DynamoDB`

**Interesting bit:** the model is only one piece of the system. Orchestration, storage, state, failure handling, and report generation matter just as much.

---

## 🔎 [Internship Monitor](https://github.com/OmerNYU/Internship-Monitor)

**An internship discovery and monitoring engine.**

It collects structured listings, evaluates relevance and likely eligibility, tracks listing state, groups opportunities, and safely queues explainable alerts.

`Python` `SQLite` `GitHub Actions` `asyncio`

**Interesting bit:** it's built around explicit source health, deterministic decisions, durable state, retries, and safe failure modes.

---

## ⚽ [MatchLens](https://github.com/OmerNYU/Match-Lens)

**Premier League prediction without pretending time doesn't exist.**

MatchLens experiments with football outcome prediction using chronological evaluation, pre-match rolling features, leakage guards, baselines, and walk-forward analysis.

`Python` `scikit-learn` `pandas`

**Interesting bit:** correctness of the experiment matters more than getting an impressive-looking accuracy number.

Also, draws are annoying.

---

## 🔥 [Kaboom](https://github.com/OmerNYU/Kaboom_Diffusion)

**A tiny C++ ray-marched fireball renderer.**

Kaboom uses signed distance fields, sphere tracing, finite-difference normals, procedural noise, and a hand-built rendering loop to generate an animated fireball.

`C++` `SDFs` `Ray Marching` `OpenMP`

**Interesting bit:** no game engine and no GPU API. Just math, pixels, and C++.

---

# How I like to build

```text
start simple
    ↓
make it measurable
    ↓
find where it fails
    ↓
stare at logs
    ↓
question previous life choices
    ↓
design for those failures
    ↓
then add complexity
```

### Evaluation > vibes

If a model looks good in a demo but the evaluation is broken, the demo doesn't mean much.

### Uncertainty is useful information

Sometimes the correct output from an ML system really is:

> *"I don't know."*

I think software should be allowed to admit that more often.

### Baselines are underrated

I'd rather understand why logistic regression works than hide a bad experiment behind a larger model.

### Failure modes belong in the architecture

Retries, abstention, validation, state transitions, health checks, and human review aren't afterthoughts.

### The system around the model matters

APIs, databases, queues, containers, tests, observability, deployment, and SQL usually determine whether ML actually becomes a product.

---

# Toolbox

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square\&logo=postgresql\&logoColor=white)

### ML / Data

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)

### Full-Stack / Backend

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=nodedotjs\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)

### Systems / Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonwebservices\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

### Robotics / Compute

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square\&logo=ros\&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square\&logo=nvidia\&logoColor=white)

---

# ✍️ The Epoch

I write about machine learning and software systems, especially ideas that become more interesting once you actually try to make them work.

### [Backpropagation from First Principles](https://omerhayat.hashnode.dev/backpropagation-from-first-principles)

An attempt to understand neural-network training without treating automatic differentiation as magic.

### Why Machine Learning Models Should Be Allowed to Say "I Don't Know"

Confidence, calibration, abstention, human review, and why forcing a model to always answer can be the wrong product decision.

**→ [Read The Epoch](https://omerhayat.hashnode.dev/)**

---

# Outside the terminal

```python
omer = {
    "usually_thinking_about": [
        "ML systems",
        "robotics",
        "software architecture",
        "cloud infrastructure",
        "why this test passed locally",
    ],
    "probably_watching": "football",
    "weakness": "turning small project ideas into full systems",
    "preferred_model_output": "calibrated",
    "preferred_git_status": "clean",
}
```

---

<div align="center">

### Still figuring things out. Building while I do.

<br>

<a href="https://omerhayat-portfolio.vercel.app/">Website</a>
  ·   <a href="https://www.linkedin.com/in/omer-hayat-974678204/">LinkedIn</a>
  ·   <a href="https://omerhayat.hashnode.dev/">The Epoch</a>
  ·   <a href="https://github.com/OmerNYU">GitHub</a>

</div>
