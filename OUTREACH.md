# Outreach & launch drafts

Fill the `[[BRACKETS]]`, then **you** send/post these. Replace `https://github.com/argusproof-ai/argus`,
`[[YOUR_NAME]]`, `argusproof.ai@gmail.com`. Keep the tone plain; the differentiator is
*verifiable evidence*, so lead with it.

---

## A. Launch write-up (blog / Substack / personal site)

**Title:** An AI-governance auditor that produces *signed, reproducible* evidence

Most "AI compliance" tooling produces assertions you have to take on faith — a
checklist, a slide, a PDF. I built the opposite: an auditor where **every finding
is cryptographically signed, reproducible, and verifiable by an outsider.**

It does seven checks in a pluggable harness — NYC LL144 four-fifths bias,
disparate-treatment *probes of the model itself*, k-anonymity privacy, recommender
amplification, LLM safety/refusal, accuracy/hallucination, and prompt-injection
robustness — and wraps them in the parts that make a finding actually
*governable*:

- **Point-in-time law** — audited against the statute as it stood on a given date.
- **A signed, hash-chained ledger** — anyone can re-derive every hash and signature.
- **Warrant-gated chain of custody** — no evidence intake without a valid,
  served authorization; cherry-picking is detected by a commit-then-sample proof.

It runs on real data (CFPB HMDA, the AI Incident Database) and on real models.
When I probed a frontier model it refused every harmful prompt, didn't
hallucinate, and resisted every injection technique — I report that as-is, because
honest null results are the point. On borderline hiring candidates it surfaced a
*mild* lean that, correctly, did not cross the legal threshold.

It does **not** pretend to grant the legal power to compel a company's data — that
stays with regulators. What it is: the technical instrument that's ready the moment
that authority exists, and, short of that, the most rigorous pre-deployment auditor
I could build.

Open source, Apache-2.0: `https://github.com/argusproof-ai/argus`. Run `./demo.sh` to watch the whole signed
chain end to end. Feedback from auditors and compliance teams very welcome —
`argusproof.ai@gmail.com`.

---

## B. LinkedIn / X post (short)

I open-sourced a regulator-grade AI-governance auditor.

The difference: every finding is **signed, reproducible, and independently
verifiable** — not a checklist, real evidence. 7 checks (bias, model
disparate-treatment, privacy, recommender amplification, safety, hallucination,
prompt-injection), point-in-time law, a tamper-evident chain of custody, and
commit-then-sample proofs against cherry-picking.

Runs on real data and real models. `./demo.sh` shows the whole chain.
Apache-2.0 → `https://github.com/argusproof-ai/argus`

Built for the AI-audit profession that the EU AI Act is about to require. Auditors,
compliance teams — would love your eyes on it.

---

## C. Cold email — independent auditor / boutique (primary ICP)

**Subject:** a verifiable-evidence engine for AI audits

Hi `[[NAME]]`,

I saw `[[FIRM]]` is building an AI-audit / assurance practice. I built an
open-source auditor that might be useful as your instrument: it runs the standard
checks (LL144 four-fifths, disparate-treatment model probes, privacy, recommender,
LLM safety/accuracy/injection) but its real value is that **every finding is signed,
reproducible, and verifiable by your client's counsel or a regulator** — and it
proves the data you were given wasn't cherry-picked (commit-then-sample).

It's Apache-2.0, runs in one command (`./demo.sh`), and produces a formatted PDF
report with an attestation block. Happy to walk you through it, or run a free pilot
on one of your engagements.

`[[YOUR_NAME]]` · `https://github.com/argusproof-ai/argus` · `argusproof.ai@gmail.com`

---

## D. Cold email — enterprise compliance (demand side)

**Subject:** defensible pre-deployment AI audit (EU AI Act / LL144 / Colorado)

Hi `[[NAME]]`,

If `[[COMPANY]]` deploys AI in hiring, lending, healthcare, or similar, you're in
scope for the EU AI Act, NYC Local Law 144, and the Colorado AI Act — each with
real documentation and bias-audit duties. I built an open-source auditor that
produces **signed, reproducible** evidence of where a system stands: which
obligations apply (point-in-time), a four-fifths bias audit on your own data, and
model-behaviour probes (safety, accuracy, injection) — each pinned to a tamper-
evident record you can hand to counsel or a regulator.

Would a free scoped pilot — your decision data + a model endpoint, out comes a
signed audit report — be useful? 15 minutes to show you?

`[[YOUR_NAME]]` · `https://github.com/argusproof-ai/argus` · `argusproof.ai@gmail.com`

---

## Where to post / who to contact

- **Communities:** IAPP (AI governance), ForHumanity (AI auditor certification),
  responsible-AI / AI-assurance groups, relevant subreddits, Hacker News ("Show HN").
- **Auditors:** boutiques and Big-4 emerging AI-assurance practices.
- **Enterprises:** compliance / responsible-AI leads at firms shipping high-risk AI.
- Always link `https://github.com/argusproof-ai/argus` and invite them to run `./demo.sh`.
