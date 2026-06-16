<div align="center">
 
Ethan Hunter - 
IT Student · Systems Builder · Brisbane, QLD
 
[![QUT](https://img.shields.io/badge/QUT-Bachelor%20of%20IT%20%28Computer%20Science%29-005A9C?style=flat-square)](https://www.qut.edu.au/)
[![Graduating](https://img.shields.io/badge/Graduating-Mid%202026-brightgreen?style=flat-square)]()
[![Location](https://img.shields.io/badge/Location-Brisbane%2C%20QLD-orange?style=flat-square)]()
[![Available](https://img.shields.io/badge/Status-Available%20Now-success?style=flat-square)]()
 
</div>
---
 
## About Me
 
Final-year IT (Computer Science) student at QUT, graduating mid-2026. I work across full-stack development, network security, systems integration, and blockchain, with a habit of building things end-to-end rather than stopping at the prototype stage.
 
Outside of study I run my own IT contracting work, deploying and integrating technology stacks for small businesses, POS systems, inventory management, accounting integrations, and everything in between. I like solving problems that sit at the intersection of code, infrastructure, and people.
 
---
 
## Tech Stack
 
**Languages**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
 
**Frameworks & Libraries**
 
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![ethers.js](https://img.shields.io/badge/ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white)
 
**Databases**
 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
 
**Infrastructure & Platforms**
 
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
 
---
 
## Projects

DockerDeploymentPractice
Node.js Docker PostgreSQL GitHub Actions
A containerized Express service with a public route and a Basic Auth–protected route, where credentials and the protected secret live in Azure Database for PostgreSQL rather than a .env file. Built and deployed via a full GitHub Actions CI/CD pipeline to a remote Linux server.

Multi-stage Dockerfile with a non-root runtime user and a built-in HEALTHCHECK; only DATABASE_URL is ever injected at runtime, no secrets baked into the image
Two-job GitHub Actions workflow: builds and pushes to GHCR with Buildx layer caching, then SSHs into the server via key auth, pulls the new image, restarts the container, and polls health status before completing
Config caching layer so the app doesn't hit Postgres on every request, with credentials rotatable in the DB without a rebuild or redeploy
End-to-end secrets flow documented from GitHub Secrets through to the app_config table
 
### [Crypto Arbitrage Bot](https://github.com/EthanHunt3r/Arbitrage_Testing)
`Solidity` `Python` `Web3`
 
A flash loan powered DEX arbitrage system built on Ethereum. Consists of a Solidity smart contract using the Balancer V2 Vault for 0% fee flash loans, a Python opportunity monitor scanning Uniswap V2, SushiSwap, and PancakeSwap in real time, and a full offline test suite validating the scanning logic without an RPC connection.
 
- Two-leg atomic flash loan cycle: borrow → swap A→B on DEX A → swap B→A on DEX B → repay, keep profit
- Python monitor estimates gas in USD and only flags opportunities above a configurable profit threshold
- Telegram alerting, colour-coded console output, and structured logging
- Shelved after testing, real arbitrage requires sub-millisecond latency and private mempool access that's outside weekend-project scope. The architecture is solid and documented.
---
 
### [CharityClarity dApp](https://github.com/EthanHunt3r/IFB452_VerificationApp)
`Solidity` `JavaScript` `ethers.js` `HTML`
 
A milestone-based charity escrow protocol on Ethereum (Sepolia). Donors fund campaigns, funds sit in escrow, and a registered auditor releases each milestone tranche once the charity provides evidence creating a transparent, trustless accountability layer for charitable donations.
 
- Three-contract architecture: `CampaignContract`, `EscrowContract`, `GovernanceContract`, each independently deployable and cross-wired post-deployment
- Role-based frontend with tabs that dynamically surface only the actions the connected wallet can perform (Owner / Charity / Auditor / Donor)
- Full audit trail on-chain for every milestone approval and rejection
- Built for QUT's IFB452 Blockchain unit, designed as an academic demo but documented with production security notes
---
 
## Areas of Study
 
```
├── Networks & Security       ← Enterprise network architecture, Linux-based security protocols
├── Enterprise Systems        ← Full life-cycle development, Salesforce, system administration  
├── Full-Stack Development    ← React, Django, REST APIs, database design
├── Blockchain                ← Smart contract development, DeFi protocols, Solidity
├── Business Intelligence     ← Data analysis, reporting, translating insights into strategy
└── AI/LLM Integration        ← Model training concepts, LLM integration into applications
```
 
---
 
## What I'm Looking For
 
Open to graduate and entry-level roles across:
- **DevOps / Infrastructure** — CI/CD, cloud platforms, automation
- **Software Development** — backend, full-stack, systems integration  
- **IT Support & Systems** — technical support, network administration, service desk
- **Blockchain / Web3** — smart contract development, protocol work
Brisbane-based. Available immediately.
 
---
 
<div align="center">
ethanhunterbeschel@hotmail.com &nbsp;|&nbsp; Nundah, Brisbane QLD
 
</div>

