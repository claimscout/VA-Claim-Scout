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

## Every Citation Must Be Verified

VA Claim Scout generates case citations, CFR sections, and BVA decision references as part of its analysis. **Treat every one of them as unverified until you check it against eCFR, KnowVA, or the primary decision text.** The framework is instructed to flag citations it isn't confident about (look for `⚠️ LOW CONFIDENCE CITATION`), but a citation with no warning attached is not the same as a citation that's been checked — it means the model was confident, not that the citation is correct. A confidently-worded citation can still be wrong. Verify before you or your representative rely on any of them.

---

## Works With a Living Plan

VA Claim Scout produces a **single-pass report** — a complete snapshot of your claim based on what you upload, generated once. It does not remember prior sessions and does not track what's changed over time.

**If you want to track your claim over weeks or months, keep a separate document you own** — not inside any AI session. Build it around three habits:

1. **Correction Log** — when something turns out to be wrong, record what it said, what it should say, and why.
2. **Pre-save consistency check** — before adding something new, check it against what you've already written down.
3. **Guess → confirmed conversion** — mark AI-generated outcome guesses as guesses, and update them to confirmed facts once a real decision arrives.

**This works with or without VA Claim Scout.** VACS's job is to analyze a snapshot of your records — claims, gaps, red-team language, TDIU/SMC signals. Keeping track of what's true over time, what's been corrected, and what's been confirmed is a separate job, and it belongs in a document you control and can verify by reading — not in an AI's claimed memory of a past conversation.

Use `Claim Scout, audit my living plan.` to have the framework check an existing plan like this against new records — see the framework file for what that command does.

---

## Two Versions — Pick the Right One

| Version  | Best For                                                 | Platform                                   |
| -------- | -------------------------------------------------------- | ------------------------------------------- |
| **Pro**  | Deep claim analysis, attorney prep, rater simulation     | Claude, GPT-4o, Gemini Advanced            |
| **Lite** | Any AI platform, softened language, same core capability | Free AI platforms such as Copilot and Grok |

**A note on free-tier AI platforms:** Tools like Microsoft Copilot and Grok offer powerful free services — and they make that possible by running lighter-weight models with reduced context capacity. That's not a flaw; it's how they afford to keep the lights on. VA Claim Scout Lite is built specifically to work within those limits and still delivers the analysis that matters. **The citation-confidence warning matters most here** — lighter models are more likely to fill a citation slot with something invented rather than flag it as uncertain. Verify citations from Lite runs especially carefully.

**If you have access to Claude, GPT-4o, or Gemini Advanced, start with Pro.**

---

## Files

- `VA_Claim_Scout_Pro.md` — Pro version
- `VA_Claim_Scout_Lite.md` — Lite version

---

## How to Use It

**Option 1 — Upload (easiest):** Most capable AI platforms accept file uploads. Upload the `.md` file directly, and the AI will read it automatically. Then type:
> `Claim Scout, Help`

and the welcome menu will appear.

**Option 2 — Paste:** If your platform doesn't support file uploads, open the `.md` file in any text editor, copy the full contents, and paste them into your AI chat as your first message. Then type `Claim Scout, Help` to get started.

No account required. No setup. No cost.

**After you run a report:** it's a one-time snapshot, not a self-updating record. Copy what's useful into your own living plan (see "Works With a Living Plan" above), verify every citation, and re-run VA Claim Scout later if you want a fresh audit — don't treat any single report as the ongoing source of truth for your claim.

---

## Also Filing for SSDI?

If you are also pursuing Social Security Disability Insurance benefits, **SSDI Claim Scout** (Coming Soon) is a separate companion tool built on the same framework.

- **github.com/claimscout/SSDI-Claim-Scout**

VSO note: VSOs are VA-accredited representatives and cannot represent claimants before the SSA. If you need SSA representation, you need a disability attorney or non-attorney representative who is SSA-accredited.

---

## Free and Open Source

VA Claim Scout is free to use, share, and build on. If you use it or adapt it, please reference the GitHub repo so others can find it.

**github.com/claimscout/VA-Claim-Scout**

*Want to support the work? Buy Me a Coffee: buymeacoffee.com/ClaimScout*

---

## Disclaimer

VA Claim Scout is an AI prompt framework, not a law firm. Nothing it produces is legal advice. Always consult a VSO, accredited claims agent, or VA-accredited attorney before making decisions about your claim. File claims at VA.gov.
