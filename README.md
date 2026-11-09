# Trust-X YC Demo Workspace

A standalone interactive dashboard prototype for presenting Trust-X, a commerce risk intelligence concept.

## Demo scope
- Synthetic dataset: 100 fictional customer profiles, 15 fictional merchants, and generated order assessments.
- Views: merchant overview, interactive risk-signal graph, customer profiles, policy studio, and governance concepts.
- Filtering: select a merchant to simulate tenant-scoped visibility.
- Export: download synthetic assessment rows as CSV.

## Important limitations
This is a front-end prototype using browser-generated deterministic sample data. It is **not connected to a production Trust-X API or merchant database**. The tenant filter is a demonstration affordance, not a security boundary. Risk scores, estimated exposures, clusters, and decisions are illustrative and are not validated model outputs. No real consumer information is included.

The governance view describes intended principles, not implemented controls, certifications, or legal compliance. Production would require server-side tenant isolation and authorization, access logging, retention controls, consumer notice/rights mechanisms, security review, and appropriate legal/privacy assessment.

## Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Deployment
The repository is intended to be linked to a separate Vercel project for the YC public demo.
