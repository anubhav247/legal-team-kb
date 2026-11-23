---
name: check_signature_authority
description: Work out the review tier, approvals and signatory for a contract
arguments:
  - contract_value: Total contract value in INR over the initial term (required)
  - special_terms: Unusual terms, for example uncapped liability or exclusivity
---
A contract has a total value of {{contract_value}} INR and these special terms: {{special_terms}}.
1. Search the knowledge base, then retrieve the Signature Authority Matrix and the Contract Review Process.
2. List the review tier, every required sign-off, the signatory, and whether General Counsel approval is needed.
3. Cite the documents you used. If a term is not covered, say so and name the right legal contact.
