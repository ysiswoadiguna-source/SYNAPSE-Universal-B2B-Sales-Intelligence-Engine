# SYNAPSE Universal B2B Sales Intelligence Engine

**An AI sales judgment engine for B2B teams.** SYNAPSE helps analyze customer conversations, qualify opportunities, identify buying signals and deal risks, understand decision dynamics, plan negotiations, and choose the next best sales action.

**Less guessing. Smarter selling. Better decisions.**

**Current version: 26.6.0** · see [Changelog](#changelog)

## 🇬🇧 English | 🇮🇩 Bahasa Indonesia

Choose the integration guide in your preferred language:

- 🇬🇧 [English — Integration Guide](SYNAPSE-INTEGRATION-GUIDE.md)
- 🇮🇩 [Bahasa Indonesia — Panduan Integrasi](PANDUAN-INTEGRASI-SYNAPSE.md)

## 🚀 Integration Guide | Panduan Integrasi

SYNAPSE works as **one Markdown Skill file**. `SKILL.md` contains the complete operating framework and runs on its own. From 26.6.0 an optional `references/` folder adds expert depth (qualification, negotiation, extended playbooks, a signal dictionary, domain notes) that the model reads only when a case needs it.

Supported setup paths:

- [ChatGPT Projects](https://chatgpt.com/)
- [Google Gemini Skills](https://gemini.google.com/)
- [Claude Skills](https://claude.ai/)

For step-by-step setup, choose the [English guide](SYNAPSE-INTEGRATION-GUIDE.md) or [Indonesian guide](PANDUAN-INTEGRASI-SYNAPSE.md).

## What SYNAPSE Helps With

- Customer conversation and opportunity analysis
- Buying-signal, objection, and deal-risk identification
- Buying-center and decision-process assessment
- Negotiation and follow-up strategy
- Opportunity probability and confidence assessment
- Next Best Action recommendations
- Natural, customer-ready messages based on the actual sales context

## 📄 Core Skill File

- [`SKILL.md`](SKILL.md) — the core Skill. It contains the operating instructions and the SYNAPSE knowledge base, and is complete on its own.
- [`references/`](references/) — optional depth, loaded on demand: [`qualification.md`](references/qualification.md), [`negotiation.md`](references/negotiation.md), [`playbooks.md`](references/playbooks.md), [`signals.md`](references/signals.md), [`domains.md`](references/domains.md).
- [`evals/`](evals/) — five test cases with pass/fail checks, for verifying a change before release. Not needed to use the Skill.

Upload `SKILL.md` to your AI platform's Skill workflow; add the `references/` files where the platform accepts more than one file. For ChatGPT Projects, upload it as a project source and add the short project instruction provided in the integration guide. Follow the target platform's current upload flow; some Claude upload paths require `SKILL.md` (and `references/`) to be placed in a folder and packaged as a ZIP.

## Operating Principles

SYNAPSE prioritizes evidence over assumptions, separates facts from claims and inferences, avoids inventing missing information, and recommends actions based on the customer's actual stage. Probability and confidence are assessed separately; a deal is never treated as certain before it is closed.

## Responsible Use

Review AI-generated analysis before acting on it. Do not upload confidential customer or company information unless you are authorized to do so and the platform's data settings are appropriate. Different AI platforms may express the same framework differently, so test the Skill with representative examples.

## Changelog

### 26.6.0
- **Core plus references.** `SKILL.md` stays short and self-sufficient; five reference files hold the depth and are read only when the case calls for them. Single-file installs keep working with `SKILL.md` alone.
- **Evidence-based probability.** The stage anchors are now adjusted by seven qualifiers (need, spec, access, budget, dated trigger, decision process, alternative), with two caps and a confidence rule tied to how many qualifiers are evidenced. The anchors are labelled as starting values to be calibrated against real win/loss history.
- **Next-move priority order.** Answer the customer, deliver what we owe, respect their date, ask for the missing qualifier — otherwise do not send.
- **Negotiation method.** Diagnose the type of price pressure first; concession plan with give-get trades; scope before margin; like-for-like comparison checklist; objection table. The floor, discount authority, and payment terms must come from the user.
- **Calc mode rules.** Fixed calculation order, no assumed tax rate, double-checked arithmetic, mismatches shown rather than silently corrected.
- **Pre-send check** before every draft, and new short playbooks for new inquiries and lost or dormant deals. Extended playbooks cover follow-up cadence, delays, overdue payment, handovers, and meeting prep.
- **Signal dictionary restored** as a reference: ambiguous customer phrases and behaviours, their possible meanings, and the question that separates them.
- **Language.** Drafts follow the language of the customer's thread; Indonesian remains the default.
- **Wider trigger description**, including short Indonesian and English asks about a specific customer.
- **Test cases** added under `evals/` (five cases, 28 checks).
- Frontmatter `name` stays `synapse-sales-intelligence`.

### 26.5.0
- **Rewritten and condensed.** `SKILL.md` is about half the length of 26.4.1 (≈108 lines vs ≈204). The numbered Part A / Part B / Part C layout is replaced by short thematic sections, so the model reads the whole framework instead of skimming it.
- **Sharper trigger description.** The Skill now states exactly when to activate: a pasted CRM record, WhatsApp chat, or email thread where the user wants a reply, follow-up, diagnosis, probability read, negotiation position, or quotation block.
- **Situation playbooks** group intermediaries and traders, tenders/e-proc/KSO, purchasing, PO received, delivery and payment, service complaints, and other industries in one place.
- **Analyze mode** keeps the buying-journey stages, buying-center roles, disqualification triggers, objection method, scenario analysis, commitment ladder, and full diagnosis checklist in compact form.
- **Lifting equipment** checklist kept as its own section (capacity, lifting height vs chain length, span, duty class, power supply, compatibility, nameplate, installation scope, verified lead time, protection parts).
- **Phrasebank trimmed** to a short set of rotating example phrases; the "don't open with *izin*" rule from 26.4.1 is kept.
- **Removed for brevity:** the relationship-state list, the separate ethics and failure-mode sections, and parts of the signal dictionary. Their core rules (no fake urgency, no unverified claims, case isolation, no reflex discounting) are folded into the remaining sections.
- Frontmatter `name` stays `synapse-sales-intelligence`, so existing installs and the ZIP folder name in the guides do not change.

### 26.4.1
- Communication-style patch for more natural customer-facing messages, including avoiding "izin" as a default WhatsApp opener.

## Repository

[GitHub Repository](https://github.com/ysiswoadiguna-source/SYNAPSE-Universal-B2B-Sales-Intelligence-Engine)

## Credits

Version 26.6.0 was co-developed with **Claude Fable 5.2** (Anthropic), which wrote the reference files, the test cases, and the 26.6.0 revision of `SKILL.md` under the author's direction.

— Claude Fable 5.2
