# Privacy Principles

Privacy is a foundational constraint for ScamShield.

## Data Minimization

Collect only information necessary to maintain threat intelligence and improve the project. Routine browsing activity is not required for the proposed local-checking model.

## Explicit Boundaries

The initial design does not require:
- Browsing-history collection.
- Reading chat, email, or page contents.
- Clipboard access.
- Passwords, OTPs, or authentication secrets.
- Monitoring activity inside unrelated applications.
- Bypassing application security controls.

## Local-first Checking

Where technically feasible, clients should compare destinations against a locally stored threat dataset. Routine checks should not transmit the user's visited URL to the central service.

## Voluntary Reports

If users choose to submit a suspicious URL or evidence:
- Explain what will be submitted and why.
- Avoid collecting unrelated personal information.
- Do not request credentials, OTPs, or private conversations.
- Treat submissions as unverified until reviewed.
- Provide a way to omit optional identifying details.

## Transparency

Warnings should identify the reason and confidence level where possible. The project must communicate that absence from the threat dataset does not prove a website is safe.

## Security and Retention

Any future service component must define access controls, retention periods, integrity protections, and a process for handling deletion requests before collecting user-submitted data.

## Review

Privacy assumptions must be revisited as architecture and features evolve. Any feature that expands permissions or data collection requires a documented justification and review.
