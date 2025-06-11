# Allocator Bookkeeping Repository for ChimsenCorp Open Data Allocator

This repository serves as the bookkeeping hub for the ChimsenCorp Open Data Allocator, outlining our policies, procedures, and requirements for DataCap allocation on the Filecoin network. We focus on facilitating the storage of open, public datasets for research, non-profit, and community-driven initiatives.

## Allocator JSON Link
[Link to ChimsenCorp Open Data Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators/ChimsenCorp-Open-Data)  
*Note: Replace with the actual link once registered in the Allocator-Registry repository.*

## Client Diligence
ChimsenCorp Open Data Allocator employs a rigorous process to verify clients, establish trust, and mitigate risks such as Sybil attacks. Our client diligence mechanism is designed to ensure only legitimate data owners are onboarded.

- **Verification Process**:
    - **KYB (Know Your Business)**: Enterprise clients must submit:
        - Registration certificates.
        - Incorporation details and company documents.
        - Government-issued business ID numbers.
        - Proof of authorized signers (e.g., board resolutions or executive letters).
    - **KYC (Know Your Customer)**: Individual clients must provide:
        - Government-issued photo ID (e.g., passport or driver’s license).
        - A selfie holding the ID for identity confirmation.
    - **Video Verification**: All clients undergo a mandatory video call to confirm identity and discuss data storage intentions.
- **Mitigating Sybil Attacks**:
    - **Rate Limits**: DataCap is allocated in phases (10% initial, 20% second, 30% third, 40% final), with a maximum of 1 PiB per client, preventing rapid over-allocation to unverified entities.
    - **Geographic Distribution**: Clients must store data across at least 3 distinct geographic regions, verified using [DataCapStats.io](https://datacapstats.io) and CID Checker Bot, to prevent location spoofing.
- **Data Ownership Verification**:
    - Clients submit data samples and ownership documentation (e.g., dataset creation records or licensing agreements).
    - KYB/KYC processes cross-check ownership claims to ensure clients are legitimate data owners.
- **Audit Evidence**:
    - Records of KYB/KYC documents, video call summaries, and geographic distribution audits are securely stored.
    - These records are provided to the Filecoin Plus Governance Team during audits to demonstrate due diligence.

## Description of Data Diligence
ChimsenCorp ensures that all data stored through our pathway meets Filecoin Plus program scope, complies with legal requirements, and aligns with client claims. Our data diligence process is thorough and transparent.

- **Data Verification Process**:
    - **Data Sampling**: Random sampling of datasets is conducted during storage deals to verify content integrity and compliance with client claims.
    - **Compliance Review**: Data samples are evaluated to ensure adherence to local and regional legal requirements, particularly for open datasets (e.g., no copyrighted material without proper licensing).
    - **Ownership Confirmation**: Clients provide proof of data ownership via KYB/KYC documentation and dataset metadata (e.g., research publication records or open-source licenses).
- **Supported Data Types**:
    - Public open datasets for research (e.g., scientific or academic data).
    - Non-profit or community-driven datasets with social impact.
    - Public commercial data with open access (e.g., public APIs or shared analytics).
- **Tools Used**:
    - **[DataCapStats.io](https://datacapstats.io)**: Tracks DataCap usage and verifies storage deal parameters.
    - **CID Checker Bot**: Validates Content Identifiers (CIDs) and retrieval rates to ensure data matches client claims.
    - **Filecoin Network Tools**: Monitor redundancy and geographic distribution of stored data.
- **Audit Evidence**:
    - Logs of data sampling results, compliance review reports, and deal verification records are maintained.
    - These records are shared with the Governance Team during audits to prove data diligence.

## Short Description of Pathway for Clients
ChimsenCorp Open Data Allocator is your trusted partner for storing open, public datasets on the Filecoin network. We specialize in supporting researchers, non-profits, and developers with streamlined onboarding, robust compliance, and geographically diverse storage. Our transparent DataCap allocation and rigorous verification ensure your data is secure, accessible, and impactful. Choose ChimsenCorp to amplify the reach of your open data initiatives.

## Contact Info
Clients can reach ChimsenCorp Open Data Allocator via:
- **Slack**: `filecoin hammer`
- **Email**: samyinfg@gmail.com
- **GitHub**: [beatyman](https://github.com/beatyman)
- **GitHub Issues**: Open an issue in the ChimsenCorp repository for inquiries.

## Detailed Allocator Policies, Procedures, and Requirements
- **KYB/KYC Requirements**:
    - **Business Clients**: Submit registration certificates, incorporation details, government-issued business ID numbers, and proof of authorized signers.
    - **Individual Clients**: Provide government-issued photo ID and a selfie with the ID.
    - **Video Verification**: Mandatory for all clients to confirm identity.
- **Data Requirements**:
    - Minimum of 5 data replicas per dataset.
    - Data must be stored across at least 3 distinct geographic regions.
    - Each storage provider (SP) receives no more than 30% of a client’s DataCap allocation per round.
    - VPN usage is permitted for access, but location spoofing is strictly prohibited.
- **DataCap Allocation**:
    - **Phase 1**: 10% of requested DataCap.
    - **Phase 2**: 20% of requested DataCap.
    - **Phase 3**: 30% of requested DataCap.
    - **Phase 4**: 40% of requested DataCap.
    - **Maximum Allocation**: 1 PiB per client.
- **Verification Tools**:
    - [DataCapStats.io](https://datacapstats.io) for DataCap and deal tracking.
    - CID Checker Bot for CID validation and retrieval verification.

## Risk Mitigation Strategies
ChimsenCorp protects its organization, reputation, and pathway from abuse through:
- **Phased Allocation**: Gradual DataCap distribution (10%, 20%, 30%, 40%) ensures clients demonstrate compliance before receiving larger allocations.
- **Geographic Enforcement**: Data must span at least 3 regions, verified via [DataCapStats.io](https://datacapstats.io) and CID Checker Bot, preventing Sybil attacks or location spoofing.
- **Operational Security (OpSec)**:
    - KYB/KYC documents and audit logs are stored in encrypted systems with restricted access.
    - Regular security audits of internal processes.
- **Monitoring and Alerts**:
    - CID Checker Bot monitors DataCap usage and deal compliance in real-time.
    - Alerts are triggered for anomalies (e.g., excessive allocation requests or geographic non-compliance).
- **User Agreements**: Clients sign agreements committing to Filecoin Plus and ChimsenCorp policies, with clauses for termination upon non-compliance.
- **Throttling Mechanisms**: Allocation caps (1 PiB per client) and phased distribution prevent overuse or abuse.

## Dispute Resolutions
ChimsenCorp handles disputes related to DataCap allocation, data compliance, or storage deals with a transparent and accountable process:
- **Internal Disputes (Client vs. Client)**:
    - **Response Time**: Initial acknowledgment within 72 hours.
    - **Process**: Both parties submit evidence (e.g., deal records, compliance documents). ChimsenCorp reviews evidence and maintains transparency with stakeholders.
    - **Accountability**: Options include suspending DataCap, reclaiming unused quotas, or blacklisting non-compliant clients/SPs.
- **Third-Party Disputes (Against Clients/SPs)**:
    - **Response Time**: Initial acknowledgment within 72 hours.
    - **Process**: Evidence is collected, and neutral mediation (e.g., via Filecoin Foundation Governance) is introduced if needed. ChimsenCorp cooperates with other notaries or the Fil+ Governance Team, providing evidence via the public dispute tracker.
    - **Accountability**: Same as internal disputes.
- **Disputes Against ChimsenCorp**:
    - **Response Time**: Initial acknowledgment within 72 hours.
    - **Process**: Transparent review with documented evidence, involving neutral mediation if necessary. ChimsenCorp complies with the Filecoin Foundation’s public dispute tracker.
    - **Accountability**: Suspend channel access or reclaim unused DataCap, with restoration possible after rectification.
- **Documentation**: All disputes are fully documented for audit purposes and to improve future processes.

## Compliance Audit Check
ChimsenCorp ensures compliance with Filecoin Plus and pathway-specific requirements through:
- **Client Compliance**:
    - Regular re-verification of KYB/KYC documents and data ownership claims.
    - Periodic video check-ins with clients to confirm ongoing compliance.
- **Storage Provider (SP) Compliance**:
    - Verify SPs meet geographic distribution (≥3 regions) and allocation limits (≤30% per SP) using [DataCapStats.io](https://datacapstats.io) and CID Checker Bot.
    - Audit SP deal performance (e.g., retrieval rates, redundancy).
- **Monitoring**:
    - Continuous tracking of DataCap usage and storage deals via CID Checker Bot and [DataCapStats.io](https://datacapstats.io).
    - Automated alerts for non-compliance (e.g., insufficient replicas or geographic concentration).
- **Audit Records**:
    - Maintain detailed records of KYB/KYC, data sampling, deal verification, and dispute resolutions.
    - Share records with the Governance Team during audits to demonstrate compliance.
- **Rectification Process**:
    - Non-compliant clients/SPs are notified and given up to 3 weeks to rectify issues.
    - Failure to comply results in DataCap suspension or termination.