# AI CS Copilot

AI CS Copilot helps support teams draft grounded customer replies from FAQ, billing policy, and past support cases.

## Team Rules

- Customer-facing answer prompts must be reviewed by Kim before merge.
- Refund, billing, cancellation, and contract policy answers must cite a source.
- Customer names, emails, company names, and raw conversation text must be masked before sharing logs externally.
- If FAQ confidence is below 0.72, the assistant should use the fallback answer instead of guessing.
- VIP customer incidents should be handled before non-urgent copy or UI polish tasks.
- Prompt changes need regression checks on at least 20 support cases before release.
 
