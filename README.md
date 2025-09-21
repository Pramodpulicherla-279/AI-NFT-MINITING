# AI-NFT-MINTING

📖 Digital Library with NFT-Signed Assets

PPT : https://docs.google.com/presentation/d/1hJSaLYlNNMWHZMSy8Z5qBeuTpsGLvexoQMZw3C36qTQ/edit?usp=sharing
Notion : https://www.notion.so/CODEX-2025-275b503ecf6b80cc9fe3ef6a6c9f4068?source=copy_link

A decentralized Digital Library where contributors create AI-generated images, sign them with NFTs, and protect ownership rights. Each contributor’s creativity is tokenized and secured, ensuring exclusive ownership while preventing unauthorized access.

✨ Features

🎨 AI-Powered Creativity – Contributors generate images using AI prompts.

🔗 NFT-Signed Assets – Every image is minted as an NFT on the Cardano blockchain.

🔒 Ownership Protection – Contributors cannot access or duplicate others’ digital assets.

🌍 Decentralized Library – Transparent, immutable, and verifiable on-chain records.

📂 Secure Metadata Storage – Assets linked to IPFS/DB with CIP-25 metadata standard.

🏗️ Tech Stack

Frontend → Next.js + React + Tailwind CSS

Blockchain → Cardano + MeshJS + Blockfrost API

Smart Contract → Plutus Minting Policy (NFT signing logic)

Storage → IPFS / Database for metadata + assets

Backend → Node.js / FastAPI (API handling)

🔄**Workflow**

       ┌───────────────┐
       │ User Browser  │
       └───────┬───────┘
               │
       ┌───────▼─────────┐
       │ Frontend - React│
       │ (Next JS)       │
       └───────┬─────────┘
               │
       ┌───────▼──────────┐
       │ Backend -        │
       │ Node.js / FastAPI│
       └───────┬──────────┘
               │
       ┌───────▼───────────────┐
       │ NFT Metadata & Asset  │
       │ Storage (IPFS/DB)     │
       └───────────────────────┘

                   
**User also interacts directly with:**

       ┌─────────────────────────┐
       │ Cardano Wallet          │
       │ Nami                    │
       └───────────┬─────────────┘
                   │
           ┌───────▼────────┐
           │ Blockchain -   │
           │ Cardano        │
           └───────┬────────┘
                   │
           ┌───────▼────────┐
           │ NFT Metadata & │
           │ Asset Storage  │
           └────────────────┘



🚀**How It Works**

**-- Contributor provides an AI prompt**

The user enters a unique description, which is sent to an AI model to generate a one-of-a-kind image.

**-- Image is minted as an NFT**

The generated image is uploaded to Firebase Storage, and its public URL is used to mint an NFT on Cardano using MeshJS.

**-- Metadata stored via CIP-25 standard**

The NFT metadata, including the image URL and prompt, is formatted according to the Cardano CIP-25 NFT standard and stored on the blockchain (optionally referencing IPFS for long-term storage).

**-- Contributor owns the signed NFT**

The NFT is sent directly to the contributor’s Cardano wallet, giving them verifiable ownership.

**-- Digital assets are protected**

Each contributor’s assets are isolated—there is no cross-access between contributors, ensuring privacy and security.

**-- Optional additions for clarity:**

**a. Wallet Integration:**

Contributors connect their Cardano wallet (via MeshJS) to receive and manage their NFTs.

**b. Preview Before Minting:**

Contributors can preview the generated AI image before minting it as an NFT.

**c. Collection Support:**

NFTs can be grouped into collections for easier discovery and management (if you support this).

**d. Open Source & Extensible:**

The platform is open source and can be extended to support other storage backends (e.g., IPFS, Arweave) or blockchains.

🤝 **Contributors**

-- We welcome all creative contributors to join and showcase their AI + NFT-powered artworks.

-- Submit your AI-generated image

-- Mint via provided DApp

-- Showcase in Digital Library
