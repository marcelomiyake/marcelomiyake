# Software architecture, distributed systems & AI in practice

This GitHub is my workspace for engineering experiments and reference implementations: distributed services, cloud deployment, and AI coding workflows. You'll find code alongside specifications, architecture decisions, and verification records.

To be clear: **my goal lately isn't to use GitHub to build production-ready projects**. Over the last few months, I have wanted to improve the process for working with AI tools and practices—testing spec-driven approaches, agent harnesses, and bounded feedback loops—and seeing whether it is possible to get good results with cheap models.

All of these projects include guardrails for code quality, and **all of them were deployed on Kubernetes**. Most repositories feature real screenshots of the systems running in the cluster. That said, **they probably have plenty of bugs!** Passing local quality gates and spinning up in a test cluster does not mean production reliability; they are practical sandboxes for studying system design, failure modes, and AI developer workflows.

My background spans more than 20 years in software engineering, including mission-critical systems at Atech. That experience connects these experiments with the questions I care about: what the software must preserve, how its parts interact, and what evidence supports a design decision.

[Read the case studies](https://marcelomiyake.com.br/) · [Professional background](https://www.linkedin.com/in/marcelomiyake/)

## What You'll Find Here

| Work | What it shows about my approach |
| :--- | :--- |
| **Five AI-built hotel systems** — [Quality study](https://marcelomiyake.com.br/posts/five-ai-hotel-implementations/) · [Maintenance study](https://marcelomiyake.com.br/posts/five-ai-hotel-implementations-part-2/) | I compare architectures by inspecting business behavior, reproducing concurrency defects, and checking whether a new feature answers the original business question. |
| **[Rust + Vue microservices template](https://github.com/marcelomiyake/microservices-template)** | I connect application structure, API contracts, architecture decisions, agent guidance, and local Kubernetes deployment in one reference project. |
| **[Autonomous Rust solver pipeline](https://github.com/marcelomiyake/autonomous-rust-leetcode-solver-pipeline)** | I explore coding automation through bounded repair loops, compiler feedback, credential handling, and gated publication in an educational workflow. |
| **[Notification system](https://github.com/marcelomiyake/notification-system)** | I examine delivery behavior through idempotency, outbox dispatch, retries, and delivery history, using local recording adapters. |

These public projects are learning and reference implementations. Their documentation identifies local verification results and remaining production requirements.

## Engineering Approach

- **Start with the business behavior:** make requirements, invariants, and acceptance criteria explicit before judging an implementation.
- **Connect the whole system:** consider APIs, data ownership, concurrency, failure handling, and deployment alongside application code.
- **Use AI with an engineering feedback loop:** combine context, contracts, compiler feedback, and bounded repair loops with verification of the resulting behavior.
- **Make decisions inspectable:** document architectural trade-offs, reproducible checks, and the limits of the evidence so others can review and build on the work.

The case studies and reference projects above put these concerns into concrete examples. I share them in English and Portuguese.

## Experience Behind the Work

**Software Engineering Specialist & Systems Architect · São Paulo, Brazil**

My experience includes over 13 years at Atech and earlier work in banking systems:

- Led full-stack development of a new air traffic management interface using Spring Boot and Vue.js.
- Developed and maintained air traffic control and simulation training systems using C, Java, and DDS, working with ICAO standards.
- Designed GCP cloud infrastructure in Go for Embraer's Digital Defense project.
- Collaborated with Airbus engineers on C++ embedded software for the EC725 helicopter under DO-178B requirements.
- Earlier work includes ATM and PIN Pad software, ISO 8583 transaction processing, and banking systems.

## Technologies & Domains

| Domain | Technologies & Standards |
| :--- | :--- |
| **Languages** | Rust, C, C++, Go, Java (Spring Boot), Python, TypeScript |
| **Cloud & Distributed Systems** | Kubernetes, GCP, Docker, Istio, DDS, Helm, Microservices |
| **AI Engineering** | Harness Engineering, MCP, AI Gateways, Model Routing, Prompt/Context Design |
| **Mission-Critical & Industry** | Air Traffic Management (ICAO), Avionics (DO-178B), Banking/ATM (ISO 8583) |

## AI Authorship & Evidence

This README, my blog articles, and the code in my public repositories are generated with AI. The case studies document source revisions, executed checks, reported measurements, and limitations. They distinguish observed behavior from claims and hypotheses; passing a local quality gate does not establish production reliability.

## Recognition & Education

- **2nd Place** — NASA International Space Apps Challenge (São Paulo, 2019)
- **MBA in Business Management** — FGV
- **Web Development & Electronics** — UNIBTA / Liceu de Artes e Ofícios de São Paulo

## Contact

- Blog: [marcelomiyake.com.br](https://marcelomiyake.com.br/)
- LinkedIn: [linkedin.com/in/marcelomiyake](https://www.linkedin.com/in/marcelomiyake/)
- X: [@MarceloMIYAKE](https://twitter.com/MarceloMIYAKE)
- Email: [marcelo.m.miyake@gmail.com](mailto:marcelo.m.miyake@gmail.com)
