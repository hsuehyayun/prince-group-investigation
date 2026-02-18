# Prince Group Transnational Money Laundering Investigation

## Overview
Independent on-chain investigation analyzing the Prince Group case, one of the largest cryptocurrency money laundering operations in history. US DOJ seized approximately **USD 15 billion** in cryptocurrency in October 2025, marking the largest crypto seizure in US law enforcement history.

## Case Background
- **Perpetrator**: Chen Zhi (陳志), 37, Fujian-born Chinese national
- **Criminal Enterprise**: Operated 10+ scam compounds across Cambodia, Myanmar, and Laos
- **Scope**: "Pig butchering" scams, human trafficking, forced labor, cryptocurrency money laundering
- **Taiwan Connection**: 9 companies registered in Taipei (和平大苑) sanctioned by Taiwan authorities
- **Timeline**: Arrested January 2026, extradited to China; US indictment October 2025

## Investigation Objectives
This project aims to:
1. **Trace cryptocurrency flows** through the Prince Group's money laundering network
2. **Identify intermediary wallets** and mixing services used for obfuscation
3. **Analyze the role of Taiwan-registered entities** in facilitating laundering operations
4. **Document fund movement patterns** from scam proceeds to legitimate financial systems
5. **Identify regulatory gaps** that enabled this transnational operation

## Methodology

### Data Sources
- US Department of Justice indictment documents (October 2025)
- Blockchain transaction data (Bitcoin, Ethereum)
- Public reporting from Chainalysis and other blockchain intelligence firms
- Taiwan Financial Supervisory Commission sanctions list
- International media coverage and investigative journalism

### Analysis Tools & Techniques
- **Blockchain Explorers**: Etherscan.io, Blockchain.com, Blockchair
- **On-chain Analysis**: Breadcrumbs.app, manual wallet clustering
- **Network Analysis**: Python (NetworkX) for transaction graph visualization
- **Data Processing**: Python (Pandas, NumPy) for transaction pattern analysis
- **Visualization**: Matplotlib, Plotly for fund flow diagrams

### Analytical Framework
1. **Wallet Identification**: Extract known addresses from DOJ documents and public sources
2. **Transaction Tracking**: Follow fund flows through successive wallet hops
3. **Cluster Analysis**: Identify wallet clusters likely controlled by same entity
4. **Pattern Recognition**: Detect mixing services, peel chains, and layering techniques
5. **Cash-out Analysis**: Trace connections to exchanges and OTC desks

## Research Questions
- How did funds move from scam victims to the Prince Group's control?
- What money laundering techniques were employed (mixing, peel chains, cross-chain bridges)?
- What role did Taiwan-registered companies play in the laundering network?
- Which cryptocurrency exchanges were used for cash-out operations?
- What regulatory weaknesses enabled this operation to scale to USD 15 billion?

## Current Status
**Phase 1: Data Collection & Literature Review** (In Progress - February 2026)
- [x] Collected DOJ indictment documents
- [x] Compiled timeline of events from public sources
- [ ] Identified initial wallet addresses from public reporting
- [ ] Extract transaction data for identified addresses
- [ ] Build preliminary transaction network graph

**Phase 2: On-Chain Analysis** (Planned - March 2026)
- [ ] Trace fund flows from known scam wallet addresses
- [ ] Identify mixing services and intermediary wallets
- [ ] Map connections to Taiwan entities
- [ ] Document cash-out pathways to exchanges

**Phase 3: Reporting & Visualization** (Planned - March-April 2026)
- [ ] Create network visualization of fund flows
- [ ] Write comprehensive case study report
- [ ] Document key findings and regulatory recommendations
- [ ] Prepare presentation materials

## Repository Structure
```
prince-group-investigation/
├── README.md                          # This file
├── data/
│   ├── addresses/                     # Known wallet addresses
│   ├── transactions/                  # Transaction data (CSV format)
│   └── sources/                       # DOJ documents, news articles
├── analysis/
│   ├── notebooks/                     # Jupyter notebooks for analysis
│   ├── scripts/                       # Python analysis scripts
│   └── visualization/                 # Charts and network graphs
├── docs/
│   ├── timeline.md                    # Chronological timeline of events
│   ├── entities.md                    # List of entities involved
│   └── methodology.md                 # Detailed methodology documentation
└── reports/
    └── case-study.md                  # Main case study report (in progress)
```

## Key Findings
*Analysis in progress. Preliminary findings will be documented here as the investigation proceeds.*

### Preliminary Observations
- The Prince Group operation demonstrated sophisticated use of cryptocurrency mixing techniques
- Taiwan-registered entities appear to have served as corporate shells for fund movements
- Multiple blockchain networks were utilized to obscure fund trails
- Large-scale operations required coordination with complicit cryptocurrency service providers

## References & Sources
- US Department of Justice Press Release (October 2025)
- Taiwan Financial Supervisory Commission Sanctions Announcement
- Chainalysis Public Analysis of Prince Group Case
- BBC, Reuters, South China Morning Post investigative reporting
- Academic literature on cryptocurrency money laundering typologies

## Legal & Ethical Considerations
This investigation is conducted for **educational and research purposes only**. All data analyzed is obtained from:
- Publicly available court documents
- Public blockchain transaction data (Bitcoin, Ethereum are public ledgers)
- Published news reporting and analysis

This project does not:
- Attempt to de-anonymize victims or non-public individuals
- Conduct unauthorized access to private systems or data
- Interfere with ongoing law enforcement investigations

## Technical Stack
- **Programming**: Python 3.9+
- **Libraries**: Pandas, NumPy, NetworkX, Matplotlib, Requests
- **Blockchain APIs**: Etherscan API, Blockchain.info API
- **Version Control**: Git, GitHub
- **Documentation**: Markdown, Jupyter Notebook

## Contact & Collaboration
This project is developed as part of academic research in financial crime investigation and blockchain forensics. 

**Author**: Ya-Yun Hsueh  
**Institution**: University of Edinburgh, MSc Banking Innovation and Risk Analytics  
**Focus Area**: Cryptocurrency forensics, AML/CFT, cross-border financial crime

For questions or collaboration inquiries: S2826670@ed.ac.uk

## License
This research project is shared for educational purposes. All original analysis and code are available under MIT License. Source documents and data remain under their original copyright and licensing terms.

---

**Last Updated**: February 17, 2026  
**Status**: Active Research Project - Phase 1 Data Collection
