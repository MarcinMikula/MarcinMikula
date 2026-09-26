### Quality Assurance Engineer exploring AI-assisted quality engineering — 13+ years across telco, banking, insurance & ecom.

I use these repositories primarily as a **learning and engineering workspace**.

My goal is not to collect technologies or build impressive demos as quickly as possible. I use the projects to organise and deepen what I already know about software testing and automation, while deliberately expanding into Python, AI and LLM-based systems.

A large part of that learning happens through building and questioning things:

* revisiting software-testing and automation fundamentals in working code,
* improving my Python and engineering skills through real implementation problems,
* learning how modern AI systems work by testing where they help, where they fail, and where deterministic controls are still necessary,
* turning useful experiments into practical QA tools.

The result is gradually becoming a small, internally consistent testing ecosystem rather than a collection of unrelated repositories.

```text
enterprise testing experience
        ↓
testing & automation fundamentals
        ↓
Python / Playwright / pytest / APIs
        ↓
LLM-assisted experimentation
        ↓
practical QA tools
        ↓
more questions → more learning
```

---

### 🔭 What I'm building

| Project                                                                                    | What it does                                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🔥 **[PhoenixQA](https://github.com/MarcinMikula/PhoenixQA)**                              | AI-assisted self-healing test automation framework with Safe/Autonomous execution, failure classification, controlled recovery strategies, and measurable healing experiments.                           |
| 🐛 **[defect-pilot](https://github.com/MarcinMikula/defect-pilot)**                        | Privacy-first Jira defect enrichment assistant that checks ticket completeness, identifies critical gaps, safely enriches available context, and routes actionable defects using explicit project rules. |
| 🧪 **[llm-qa-toolkit](https://github.com/MarcinMikula/llm-qa-toolkit)**                    | Experimental LLM evaluation framework exploring Test Basis, evaluator authority, evidence, gradability and the limits of LLM-as-a-judge approaches.                                                      |
| 🏗️ **[qa-automation-framework](https://github.com/MarcinMikula/qa-automation-framework)** | Reusable Playwright + pytest automation skeleton built around POM/SOM principles and enterprise-style UI/API testing.                                                                                    |

These are not intended to be isolated demos.

`qa-automation-framework` provides reusable automation structure. `PhoenixQA` explores runtime recovery and maintenance. `defect-pilot` explores defect-quality workflows. `llm-qa-toolkit` turns the same testing mindset toward AI systems themselves.

Different problems, but the same underlying question:

> **How can AI support software testing without replacing evidence, engineering discipline and human control?**

---

### 🧠 How I work

I use AI heavily, but I don't treat generated code or generated conclusions as a black box.

My background is software testing rather than software development, so I approach these projects primarily through **SDLC/STLC, risk, testability and evidence**. I bring practical experience with enterprise systems, SQL, REST/SOAP integrations and test design, while deliberately expanding the programming side through Python, Playwright, pytest and related tooling.

For automation I try to preserve familiar engineering boundaries such as **Page Objects, Service Objects, separation of test data and logic, deterministic checks, explicit acceptance criteria and regression evidence**.

I rarely treat the first technically working solution as the final one. Before claiming that an approach works, I try to understand the alternatives, assumptions and failure modes behind it — and, where possible, test them against evidence.

That sometimes makes the projects slower and more exploratory than a typical implementation project. A feature may lead to a diagnostic experiment, an architectural change, a rejected approach or even a reduction in project scope. I consider that part of the engineering work rather than wasted effort.

I prefer a smaller claim supported by evidence over a more impressive claim supported only by working code.

A seemingly small implementation question can therefore turn into:

```text
implementation
    ↓
unexpected behaviour
    ↓
test
    ↓
architectural question
    ↓
alternative approaches
    ↓
experiment
    ↓
documented limitation
    ↓
new hypothesis
```

That reasoning is deliberately preserved in files such as `LEARNINGS.md`, testing strategies, architecture decisions, known limitations and research hypotheses.

The repositories therefore show not only the current code, but also **how and why it evolved** — including approaches that were tested and later rejected or deliberately narrowed.

---

### 🌱 What I'm currently learning

* practical limits and useful applications of LLMs in software testing,
* reliable evaluation of AI systems and the weaknesses of `LLM-as-a-judge`,
* self-healing and maintenance of automated tests,
* human-controlled vs autonomous AI-assisted workflows,
* Python and software-design practices needed to turn QA experiments into maintainable tools,
* CI/CD, reproducibility and measurable validation of AI-assisted behaviour,
* local vs cloud LLM trade-offs for enterprise and sensitive test contexts.

A recurring principle across the projects is:

> **LLM proposes; evidence, deterministic controls and humans define what may be trusted.**

---

### 🛠️ Current toolbox

`Python` `Playwright` `pytest` `SQL` `REST` `SOAP` `POM` `SOM` `Jira API` `Ollama` `Claude / Anthropic API` `GitHub Actions` `Allure`

---

### 📍 Based in Warsaw — open to remote/hybrid roles

[nofluffjobs profile](https://nofluffjobs.com/profile/QRSIUE1X) · 
