# Locked Profile Redesign Plan

## Decisions

- **AI positioning (1C):** Keep a production RAG case study, and add a separate Agentic Learning track for in-progress AI work.
- **Banner (2B):** Keep `github-banner.png` in this pass. Plan a follow-up banner tech-strip update later.

## Theme

Dark Systems Blueprint — banner remains the visual hero; README becomes quieter, proof-first, and data-complete.

## Target Information Flow

```text
Banner (keep as-is)
  → Compact Hero (name, role, value line, CTAs, location)
  → Proof of Work (metrics)
  → Work Tracks (Backend | Blockchain | DevOps | Agentic Learning)
  → Featured Systems (4 case studies; AI RAG marked as applied/production RAG)
  → Tech Stack Map (full skill coverage)
  → GitHub Stats (reliable widgets + Top Languages + activity graph)
  → Currently Exploring (Agentic progress: tool calling done → full agent workflows)
  → Connect
```

## Section Specs

### 1. Hero

- Keep banner image.
- Keep: name + `dalton150`, role line, short value statement, LinkedIn / GitHub / Email.
- Keep location badge.
- Remove broken Profile Views counter (or replace only if a verified working endpoint is found during implementation).
- No large typing animation competing with the banner.

### 2. Proof of Work

Keep existing metrics:

- 3+ years production engineering
- 100+ trading pairs
- 70+ smart contracts
- 50+ reward systems
- Cloud / CI/CD / production deployments

Do not invent new numbers.

### 3. Work Tracks (new)

Four tracks:

1. **Backend Development (Production)**  
   Node.js, Express.js, JavaScript, MongoDB, PostgreSQL, WebSockets, Redis, REST APIs, real-time systems

2. **Blockchain Development (Production)**  
   Solidity, smart contracts, Web3.js, Ethers.js, real-time transactions, Web3 APIs, EVM-compatible chains, ERC20 / ERC721 / ERC1155 / ERC4626 / ERC2612 + EIPs, Hardhat, Foundry, IPFS

3. **DevOps & Cloud (Production)**  
   Linux, Docker, Kubernetes, GitHub Actions, Jenkins, CI/CD, AWS

4. **AI & Agentic (Learning / Exploring)**  
   AI agent integration, RAG, ChromaDB, OpenAI APIs, open-source models/frameworks  
   Progress note: Tool calling completed; continuing toward full agent workflows

### 4. Featured Systems

Keep four projects with Problem / Built / Stack / Impact:

1. Multi-Chain DEX — production
2. Binary Trading Platform — production
3. Token & Presale Ecosystem — production
4. AI Chat Backend (RAG) — keep as applied RAG work (production-style case study), not as full Agentic mastery

Expand stack chips where accurate (Redis, Postgres, ERC standards, etc.).

Do not invent repo links if projects are private; optionally label as Private / Production if needed later.

### 5. Tech Stack Map

Full grouped badges:

- Backend: Node.js, Express.js, JavaScript, WebSockets, REST API
- Databases & Cache: MongoDB, PostgreSQL, Redis
- Blockchain: Solidity, Ethereum/EVM, Ethers.js, Web3.js, Hardhat, Foundry, IPFS
- Standards: ERC20, ERC721, ERC1155, ERC4626, ERC2612
- DevOps & Cloud: Linux, Docker, Kubernetes, GitHub Actions, Jenkins, AWS, Nginx (keep if already claimed)
- AI & Agentic (Learning): OpenAI, ChromaDB, RAG, Agent Integration, open-source models/frameworks

### 6. GitHub Stats (reliability first)

Current broken sources:

- `github-readme-stats.vercel.app` → DEPLOYMENT_PAUSED
- `streak-stats.demolab.com` → 500
- `visitcount.itsvg.in` → 404

Implementation order:

1. Prefer GitHub Action generating static SVG stats into the repo (most reliable under GitHub Camo)
2. Else use a currently working public successor/host verified at implement time
3. Include: Stats card + Top Languages + Activity graph
4. Streak card only if a stable source is available
5. Keep stats below core career story (secondary section)

### 7. Currently Exploring

Short, honest progress list focused on Agentic AI:

- Tool calling completed
- Next: multi-agent orchestration, advanced RAG (hybrid search / re-ranking / memory), open-source model integration
- Optional: Rust for blockchain/systems, smart contract security (keep only if space allows)

### 8. Connect

Keep compact contact badges and closing quote.

## Out of Scope (this pass)

- Do not regenerate `github-banner.png`
- Do not change pinned repos in GitHub settings from code (manual recommendation only)
- Do not invent unverifiable project links or metrics

## Follow-up (after this pass)

1. Banner update: expand tech strip to include Redis, Kubernetes, ERC standards, ChromaDB/AI tools
2. Pin repos that match production claims (or architecture/case-study repos)
3. Optional self-hosted stats if Action-based static SVGs are preferred long-term

## Verification Checklist

- No broken images on live GitHub profile
- Full skill set visible by track
- AI honesty clear: RAG case study present + Agentic marked Learning
- Recruiter can understand role, proof, stack, and contact within 10 seconds
- Activity/stats render reliably
