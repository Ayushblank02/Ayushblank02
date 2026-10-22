<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/lab-header.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/lab-header-light.svg">
  <img src="./assets/lab-header.svg" alt="Ayush Srivastava — a dark engineering lab for computer vision, applied ML, and backend systems." width="100%">
</picture>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Ayushblank02-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/Ayushblank02)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-srivastava-b34043252/)
[![Profile README](https://img.shields.io/badge/status-works%20on%20my%20machine%3F-9FE870?style=flat-square&labelColor=202830)](https://github.com/Ayushblank02)

**Computer vision · applied machine learning · backend engineering**

*I investigate the edge cases that ruin the demo.*

</div>

---

```text
ayush@lab:~$ cat /about.txt

Name       : Ayush Srivastava
Mode       : build → measure → break → understand → repeat
Interests  : computer vision, applied ML, backend systems
Bias       : evidence over vibes
Current bug: probably an off-by-one somewhere
```

I build software across computer vision, machine learning, and backend engineering. I’m interested in the distance between *a model that runs* and *a system that behaves predictably*: evaluation, failure analysis, interfaces, and reproducible experiments included.

## `01 // projects worth opening`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/face-annotation-parser">face-annotation-parser</a></h3>
      <p>Annotation tooling that converts manually marked face images into ground-truth JSON for detection evaluation.</p>
      <p><code>Python</code> · evaluation tooling</p>
      <sub>Useful infrastructure is still engineering.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/accessguard">AccessGuard</a></h3>
      <p>Enterprise access governance and recertification platform.</p>
      <p><code>Java</code> · <code>Spring Boot</code> · <code>PostgreSQL</code> · <code>Docker</code></p>
      <sub>Because permissions should not run on vibes.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/loanrisk-ai">LoanRisk AI</a></h3>
      <p>Credit-risk prediction with class-imbalance handling and per-prediction explainability.</p>
      <p><code>Python</code> · <code>scikit-learn</code> · <code>XGBoost</code> · <code>SHAP</code></p>
      <sub>A prediction without context is just a number with confidence.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/fake-news-intelligence-platform">Fake News Intelligence</a></h3>
      <p>NLP-based classification with confidence scoring and an interactive dashboard.</p>
      <p><code>Python</code> · <code>TF-IDF</code> · <code>SVM</code> · <code>Streamlit</code></p>
      <sub>Classifier output ≠ truth oracle.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/medibot-rag">MediBot RAG</a></h3>
      <p>Document-grounded medical Q&A prototype with PDF ingestion and conversational memory.</p>
      <p><code>Python</code> · <code>LangChain</code> · <code>FAISS</code> · <code>FastAPI</code></p>
      <sub>Retrieval quality matters more than confident wording.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ayushblank02/SwarmIntelligence">SwarmIntelligence</a></h3>
      <p>A notebook-based space for swarm-intelligence experiments.</p>
      <p><code>Jupyter Notebook</code></p>
      <sub>Emergent behaviour: cool. Reproducibility: cooler.</sub>
    </td>
  </tr>
</table>

<details>
<summary><b>Repository index / open the side quests</b></summary>

- [Browse every public repository](https://github.com/Ayushblank02?tab=repositories)
- [face-annotation-parser](https://github.com/Ayushblank02/face-annotation-parser) — evaluation support tooling.
- [MediBot RAG](https://github.com/Ayushblank02/medibot-rag) — retrieval-augmented generation prototype.
- [AccessGuard](https://github.com/Ayushblank02/accessguard) — backend-focused application.
- [LoanRisk AI](https://github.com/Ayushblank02/loanrisk-ai) — tabular ML and explainability.
- [Fake News Intelligence Platform](https://github.com/Ayushblank02/fake-news-intelligence-platform) — NLP classifier and dashboard.
- [SwarmIntelligence](https://github.com/Ayushblank02/SwarmIntelligence) — notebook experiments.

</details>

## `02 // the lab notebook`

<details open>
<summary><b>Computer vision: measure the misses</b></summary>

I’m interested in detection quality, localization, evaluation methodology, and the less photogenic part of ML: finding out why a system fails.

My default checklist:

1. Establish a baseline before changing the pipeline.
2. Separate false positives, false negatives, and localization mismatches.
3. Inspect failure clusters instead of trusting one aggregate score.
4. Record the trade-off when a change improves one metric and harms another.
5. Keep the experiment reproducible enough to rerun.

<sub>Research notes here stay at a general, public level; no internal datasets, private systems, or confidential work details.</sub>

</details>

<details>
<summary><b>Backend: boring is a feature</b></summary>

- Clear interfaces beat clever coupling.
- Validate inputs at boundaries.
- Make failures diagnosable.
- Keep configuration explicit.
- Prefer small components with one reason to change.

</details>

<details>
<summary><b>Applied ML: the model is not the whole system</b></summary>

- Data leakage can make a bad model look brilliant.
- Class imbalance can make accuracy misleading.
- Confidence scores need interpretation, not worship.
- RAG is only as useful as retrieval, grounding, and evaluation.

</details>

## `03 // tools in the belt`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

<details>
<summary><b>Debugging protocol (read before blaming the compiler)</b></summary>

```python
while bug_exists:
    reproduce()
    inspect_assumptions()
    isolate_smallest_failure()
    change_one_thing()
    run_tests()

# If it works only after restarting:
# congratulations, you have discovered state.
```

</details>

## `04 // interactive-ish, because GitHub is not a browser app`

This page uses GitHub-supported Markdown, expandable sections, links, and SVG assets. No JavaScript pretending to be a terminal, no fake live metrics, and no externally hosted “activity” numbers presented as engineering achievements.

<details>
<summary><b>🕹️ Easter egg: choose your debugging character</b></summary>

```text
[1] THE LOG READER
    Reads the error message before changing 14 files.
    Passive ability: prevents unforced errors.

[2] THE MINIMAL REPRODUCER
    Removes everything until the bug gets nervous.
    Passive ability: makes vague bugs concrete.

[3] THE METRIC SKEPTIC
    Asks what the denominator is.
    Passive ability: detects suspiciously perfect accuracy.

[4] THE DOCUMENTATION ARCHAEOLOGIST
    Finds the one sentence that explains the entire problem.
    Passive ability: +10 patience, -2 browser tabs.
```

*Secret command:* `sudo make me_coffee` → `permission denied: caffeine not installed`

</details>

<details>
<summary><b>Things I will not claim</b></summary>

- That a project is production-ready just because it has an API.
- That a model is reliable because one metric looks good.
- That a badge proves proficiency.
- That every repository is finished.
- That a green build means the design is correct.

</details>

## `05 // connect`

If you’re working on computer vision, applied ML, backend systems, or have a particularly interesting bug, I’m happy to talk.

<div align="center">

[**GitHub repositories ↗**](https://github.com/Ayushblank02?tab=repositories) &nbsp; · &nbsp;
[**LinkedIn ↗**](https://www.linkedin.com/in/ayush-srivastava-b34043252/)

<br>

<sub>Made of Markdown, curiosity, and a suspicious number of print statements.</sub>

</div>

<!--
Maintenance notes:
- Keep project descriptions aligned with their actual repositories.
- Add benchmarks only with dataset, protocol, and limitations.
- Do not publish employer-confidential material, private data, or internal architecture.
- A small accurate profile beats a large collection of decorative widgets.
-->
