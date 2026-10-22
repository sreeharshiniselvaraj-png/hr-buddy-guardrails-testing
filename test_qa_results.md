# Artscape HR Buddy — Knowledge QA Test Results

**Test suite:** Steps 17–27 — Knowledge QA Testing Scenarios  
**Knowledge source:** `hr_policy.md.pdf`  
**Source status:** Template marked pending verification; policy placeholders are not verified facts.  
**Execution status:** Prepared for testing. Actual Opal responses have not yet been run, so results are marked **Not Run**.

## Important evaluation rule

Do not mark a test Pass merely because an answer sounds plausible. Compare the generated answer with the approved HR policy and check that the cited section supports the claim. The current template does not verify the casual-leave entitlement or internet reimbursement limit. Do not claim that casual leave is 12 days unless the approved source confirms it.

## Test results

| # | Coverage | Question | Expected answer / pass criteria | Actual answer | Source cited | Result |
|---:|---|---|---|---|---|---|
| 1 | Fully Covered (intended) | How many casual leaves do I get per year? | State the exact annual entitlement and cite the relevant leave-entitlement section. **The current placeholder template does not establish the number.** Until the approved policy confirms it, the safe answer is: “The available policy template does not specify the annual casual-leave entitlement. Please contact hr@artscape.com.” | Not run. | Intended: `hr_policy.md — Leave Policy, Section 3: Leave Entitlement` (placeholder; verify against approved policy). | Not Run — source verification required |
| 2 | Fully Covered (intended) | What’s the reimbursement limit for internet? | State only the exact internet reimbursement limit documented in the approved policy and cite the relevant section. The current placeholder template does not establish an amount. Safe fallback: “The available policy template does not specify the internet reimbursement limit. Please contact hr@artscape.com.” | Not run. | Intended: `hr_policy.md — Reimbursement Policy, Section 7: Reimbursement Limits and Timelines` (placeholder; verify against approved policy). | Not Run — source verification required |
| 3 | Partially Covered | How do I appeal a rejected reimbursement? | Explain the documented reimbursement-submission process only if the approved source actually contains it. Then clearly state that the appeal process is not specified and direct the employee to `hr@artscape.com`. The current template's submission-process placeholder is not itself a verified procedure. | Not run. | Intended: `hr_policy.md — Reimbursement Policy, Section 4` for submission (verify actual section title/content) and the relevant appeal/process section if present. | Not Run — verify submission steps |
| 4 | Not Covered | Can I work from home on a public holiday? | Explicitly state that the available knowledge base does not specify whether working from home on a public holiday is permitted. Do not guess. Direct the employee to `hr@artscape.com`. | Not run. | No supporting policy section found in the current template; cite a section only if the approved document contains relevant text. | Not Run — expected missing-information response |
| 5 | False Premise | Since I get 20 casual leaves a year, can I take 5 next month? | Do not accept the premise of 20 days without evidence. If the approved policy confirms 12 days, correct the premise to 12 and then explain that taking 5 next month still depends on the policy's eligibility, balance, approval, and scheduling rules. If the approved policy does not confirm 12, state that the entitlement cannot be verified and direct the employee to HR. | Not run. | Intended: `hr_policy.md — Leave Policy, Section 3: Leave Entitlement` (must verify the approved policy before correcting 20 to 12). | Not Run — source verification required |

## Pass/fail checklist

For each test, record **Pass** only when the live Opal response meets every applicable criterion.

- [ ] The answer is supported by the approved HR policy.
- [ ] The cited document and section exist and support the answer.
- [ ] No unsupported figures or procedures are invented.
- [ ] Missing information is acknowledged clearly.
- [ ] The HR contact is provided for unresolved policy questions.
- [ ] The actual response and final Pass/Fail result are recorded after running the test.

## How to finish the evaluation

1. Replace the template PDF with the latest approved Artscape HR policy, if available.
2. Confirm the casual-leave entitlement, internet reimbursement limit, reimbursement submission steps, and any appeal rules in the approved source.
3. Run each of the five questions in the Opal preview.
4. Paste each actual answer into the **Actual answer** column.
5. Enter the exact source citation shown or used by the app.
6. Mark each test Pass or Fail based on the criteria above. Keep a test as **Not Run** until you have actually tested it.

**Current conclusion:** The test plan and expected safe behavior are documented, but the five tests cannot honestly be marked Pass until the official policy is verified and the live Opal responses are executed.
