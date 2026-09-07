# Feature status — Pharmacy operations & drug reimbursement

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 125 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 9 | 0 | Native records/view |
| Activity & audit trail | audit | 9 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Contract customer registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Identifier hierarchy mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NDC product registry | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Wholesaler sales ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility date validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| WAC price comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback amount calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate claim detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Indirect customer validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wholesaler deduction matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rejection remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit memo reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Accrual true-up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wholesaler product analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NDC and drug registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wholesaler invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract acquisition-cost calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate and allowance accrual | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim and remittance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ingredient-cost validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispensing-fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benchmark comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Negative-margin detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MAC appeal eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reversal and rebill analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Specialty margin analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wholesaler credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer appeal generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovered margin ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drug payer and location analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PBM contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network amendment control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prescription claim ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance measure calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DIR estimate accrual | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DIR fee recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| GER guarantee analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand generic mix validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network rebate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remittance adjustment matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Negative balance review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pharmacy dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PBM response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PBM store analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production Day | records | 1 | 0 | Native records/view |
| Radiopharmacy Order | records | 1 | 0 | Native records/view |
| Production Lot | records | 1 | 0 | Native records/view |
| Order Lot Assignment | records | 1 | 0 | Native records/view |
| Assay Record | records | 1 | 0 | Native records/view |
| Batch Check | records | 1 | 0 | Native records/view |
| Delivery Dispatch | records | 1 | 0 | Native records/view |
| Delivery Receipt | records | 1 | 0 | Native records/view |
| Production Exception | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Order scheduling brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Batch document completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assay record reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiry conflict summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Courier handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production exception narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NDC and drug inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointment matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Administration reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NDC-to-HCPCS crosswalk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| J-code validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unit conversion calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wastage modifier control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prior authorization linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payer reimbursement calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing charge detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underpayment identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial remediation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Replacement drug tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drug payer and site analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manufacturer agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible dispense ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Patient program qualification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market-share calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adherence measure validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outcome guarantee evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data submission SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manufacturer deduction review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash collection tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program drug economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prescription Verification | records | 1 | 0 | Native records/view |
| Drug Utilization Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Management | records | 1 | 0 | Native records/view |
| Insurance Claims | records | 1 | 0 | Native records/view |
| Controlled Substances | records | 1 | 0 | Native records/view |
| Patient Management | records | 1 | 0 | Native records/view |
| Regulatory Compliance | records | 1 | 0 | Native records/view |
| Drug Interactions | records | 1 | 0 | Native records/view |
| Supplier Management | records | 1 | 0 | Native records/view |
| Staff Management | records | 1 | 0 | Native records/view |
| Adverse Event Reporting | records | 1 | 0 | Native records/view |
| Rx Transfers | records | 1 | 0 | Native records/view |
| Financial Transactions | records | 1 | 0 | Native records/view |
| Shift Scheduling | records | 1 | 0 | Native records/view |
| AI Reorder Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Formulary Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 125 feature pages were visited in the browser; 123 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 88 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

88 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
