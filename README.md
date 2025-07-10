# Fil+DC-Allocator-Allen
V5 FIL+ DC Allocator Allen Cho Zeta Cube Inc https://zetacube.net

-----
## Programmatic Policies
1. Filecoin Plus is designed for all client actors with quality data who engage in distributed onboarding. Client actors can be either data owners or preparers (including SPs), who either provide some form of KYC (and KYB) information to earn social trust or prove long-term commitment (i.e. collateral in a trustless notary).

2. The Filecoin Plus program defines 'quality data' as all content that meets local regulatory requirements AND

  - the data owner wants to see on the network, including private/encrypted data;
- or is open and retrievable;
- or demonstrates proof of concept or utility of the network, such as efforts to improve onboarding.

3. Allocators are responsible for performing diligence on their clients and datasets.

4. Each allocator pathway will be subject to an audit performed by the MetaAllocator that supervises that pathway. When the pathway has distributed 75% of the DataCap they received in the previous round, the allocator should trigger the review by submitting the appropriate template in this GitHub repo (current link).

5. Storage providers will be tested for retrievability using the Spark protocol (https://github.com/filecoin-station/spark). As an allocator, you are responsible for holding your clients accountable, and those clients are responsible for working with reputable Storage Providers that meet your onboarding, distribution, and retrieval requirements.

6. Every dataset participating in the Fil+ program should be stored in at least two different physical regions.

7. If there are no client allocations or developer progress after 2 months of approval of an allocator, that pathway's DataCap may be paused or revoked.

8. Within two weeks of approval & receiving initial DataCap allocation, each allocator must publish a Readme document detailing:

- Short description of pathway for clients, to be included in Allocator website.
- Contact info, such as Slack ID.
- Detailed Allocator policies, procedures, and requirements.
- Risk mitigation strategies - the processes for protecting your organization, reputation, and pathway from abuse. For example, what Operational Security (OpSec) standards, user agreements, alerts, or throttling mechanisms will you employ?
- Dispute Resolutions - A dispute within the context of DataCap allocation refers to any contention or disagreement arising between parties involved in the storage and retrieval of data on the Filecoin network. This could involve discrepancies over DataCap distribution, disagreements on data compliance with stated parameters, or conflicts over the execution of storage deals. Disputes may be internal, involving yourself and your client, or external, where you will need to defend your decisions against another active allocator or the Fil+ Governance Team.
- Compliance Audit Check - how do you plan to ensure that your clients, and the storage providers they interact with are all in compliance with both program-wide and pathway specific requirements.

## Compliance Audit Policies & Process
### Core Review Criteria for All Allocators
Auditors assess the Allocator's performance using on-chain data from tools like datacapstats.io and CID audits, as well as off-chain data from bookkeeping sources.

- Proposed claims versus evidence: Did the allocator uphold requirements (e.g. client types, SP relationships)?
- DataCap Distribution & Utilization:
  - Scaling trust over time
  - Number of SPs connected to clients
  - Number and size of unique datasets
  - Time clients took to use DataCap
  - Revoking unused DataCap
- Client Behavior: Did clients use listed SPs and datasets? Provenance Checks: Verifying dataset ownership (e.g. attestations, contracts)
- SP Info Gathering: KYB and diligence evidence

### Enterprise Data Evaluation Path
If the allocator supports Enterprise Data, the auditor may request:

- Client KYC: ID documents, proof of address, risk assessments, business purpose
- SP KYB: Incorporation docs, governance records, ownership proof, KYB reports
- Non-Collusion Proofs: Signed affidavits, org charts, due diligence reports
- Economic Transfer Evidence: Invoices, payment receipts, on-chain logs
All documents must show clear separation and legitimate business relationships between clients and SPs.

### Public/Open Data Evaluation Path
For Open/Public datasets, the auditor will investigate:

- Retrievability: Tested via Spark protocol (≤20ms latency, target RSR >75%); alternate proofs pending approval
- Provenance: Public URLs, digital signatures, agreements with original data sources
- Data Preparation Verification: Scripts, processing logs, and step-by-step audit trail
- Justification for uploading duplicate datasets
- Content Validation: Auditors may download and inspect stored data for authenticity
  
**Successful allocators must maintain transparency, diversity, and a strong audit trail throughout.**
