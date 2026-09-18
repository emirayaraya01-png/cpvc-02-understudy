# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page produce warehouse inventory tracker where a visitor submits a short form to add a new inventory item (product, quantity, price, perishable/expiration date), and the item appears in a sorted inventory list with FIFO order and an expiration-alert status computed automatically.
- **Audience:** A produce company's CEO and warehouse manager, who want to see exact quantities, quality, prices, FIFO alerts, and perishable timing at a glance, and add new stock as it arrives.
- **Requirements:** One working primary interaction; selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Blue-and-grey tones, Times New Roman typography, a classic/formal look (like a ledger or business report) rather than a flashy modern dashboard. Submitting the form should visibly and immediately update the sorted list below it.
- **Test:** I can submit a new item through the form and see it appear correctly placed in FIFO order with an accurate expiration alert; I can check one boundary case (e.g. two items expiring on the same date, or one expiring today); and I can confirm the standing rule holds even after adding more items.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
