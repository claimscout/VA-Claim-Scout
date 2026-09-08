# VA Claim Scout

**A free, open-source AI prompt framework for veterans navigating VA disability claims.**

VA Claim Scout gives you the analytical perspective of a VA-accredited attorney, a claims rater, and a VSO — without the cost. Load the framework into any capable AI and ask it to help you understand your records and your claim.

---

## What It Does

VA Claim Scout helps you:

- Identify conditions that may qualify for VA disability benefits
- Find secondary and presumptive claims you may have missed
- Understand the strengths and gaps in your evidence
- Prepare for C&P exams and doctor appointments
- Draft messages to your VSO, attorney, or VA representative
- Build buddy statements and impact statements that carry legal weight

It does not file claims, access your VA records, or provide legal advice. It helps you think through your claim more clearly.

---

## Critical: Treat This as a One-Shot Analysis, Not a Living Record

VA Claim Scout is deliberately designed as a **single-pass report generator**. It produces one complete analysis from the records you give it. It does not remember prior sessions and it does not maintain state across chats.

**That is a feature, not a limitation.** Persistence inside an AI prompt is a hallucination surface. The reliable place for continuity is a document *you* own and can read.

### Recommended Companion Workflow

After you run VA Claim Scout, feed the output into a separate, human-owned document that you update over time. Build that document around three disciplines:

| Discipline | What it does |
|---|---|
| **Correction Log** | Record what the AI got wrong, what you changed it to, and why. |
| **Pre-save consistency check** | Before saving any new finding, compare it against what the document already says. |
| **Guess → confirmed conversion** | Explicitly update any low-confidence or guessed outcome to a verified fact once a real VA decision, exam, or medical record arrives. Do not leave stale guesses sitting in the document. |

This pattern keeps the source of truth under your control. The AI produces the analysis; your document absorbs it, corrects it, and tracks what actually turned out to be true.

This living document is yours. It works with or without VA Claim Scout; the framework is simply one source of analysis you can feed into it.

---

## Citation Discipline (Read This Before You Trust Any Legal Citation)

When the framework produces case names, 38 CFR citations, M21-1 references, or Fast Letters, **treat every citation as unverified until you check it against a real source** (eCFR, KnowVA, or the actual decision text).

The Pro and Lite frameworks now instruct the model to flag low-confidence citations explicitly rather than invent them to fill a required format. Even so, AI models still hallucinate legal authority. Your verification step is non-negotiable.

---

## Two Versions — Pick the Right One

| Version | Best For | Platform |
|---|---|---|
| **Pro** | Deep claim analysis, attorney prep, rater simulation | Claude, GPT-4o, Gemini Advanced |
| **Lite** | Any AI platform, softened language, same core capability | Free AI platforms such as Copilot and Grok |

**A note on free-tier AI platforms:** Tools like Microsoft Copilot and Grok offer powerful free services — and they make that possible by running lighter-weight models with reduced context capacity. That is not a flaw; it is how they afford to keep the lights on. VA Claim Scout Lite is built specifically to work within those limits and still delivers the analysis that matters.

**If you have access to Claude, GPT-4o, or Gemini Advanced, start with Pro.**

---

## Files

- `VA_Claim_Scout_Pro.md` — Pro version
- `VA_Claim_Scout_Lite.md` — Lite version
- `VA Claim Scout – Quick Start Guide.pdf` — printable quick start

---

## How to Use It

**Option 1 — Upload (easiest):**  
Most capable AI platforms accept file uploads. Upload the `.md` file directly, and the AI will read it automatically. Then type:

> `Claim Scout, Help`

and the welcome menu will appear.

**Option 2 — Paste:**  
If your platform doesn’t support file uploads, open the `.md` file in any text editor, copy the full contents, and paste them into your AI chat as your first message. Then type `Claim Scout, Help` to get started.

No account required. No setup. No cost.

---

## Also Filing for SSDI?

If you are also pursuing Social Security Disability Insurance benefits, **SSDI Claim Scout** (Coming Soon) is a separate companion tool built on the same framework.

- **github.com/ClaimScout/SSDI-Claim-Scout**

VSO note: VSOs are VA-accredited representatives and cannot represent claimants before the SSA. If you need SSA representation, you need a disability attorney or non-attorney representative who is SSA-accredited.

---

## Free and Open Source

VA Claim Scout is free to use, share, and build on. If you use it or adapt it, please reference the GitHub repo so others can find it.

**github.com/ClaimScout/VA-Claim-Scout**

*Want to support the work? Buy Me a Coffee: buymeacoffee.com/ClaimScout*

---

## Disclaimer

VA Claim Scout is an AI prompt framework, not a law firm. Nothing it produces is legal advice. Always consult a VSO, accredited claims agent, or VA-accredited attorney before making decisions about your claim. File claims at VA.gov.
