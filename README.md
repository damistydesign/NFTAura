# 🔮 NFTAura - Next Gen Web3 ReFi Platform

**A full-stack, dockerized hybrid application bridging Web2 administration with Web3 ownership verification.**

## 🔒 Source Code Access / Acceso al Código Fuente

**English:**
Due to intellectual property rights and the commercial nature of this boilerplate, the source code for NFTAura is hosted in a private repository. However, I am happy to provide read-access to the repository or conduct a live code walkthrough for recruiters and technical leads during the interview process.

**Español:**
Por motivos de propiedad intelectual y la naturaleza comercial de este proyecto, el código fuente de NFTAura se encuentra en un repositorio privado.

Sin embargo, con gusto puedo otorgar acceso de lectura al repositorio o realizar un recorrido técnico en vivo del código para reclutadores y líderes técnicos durante el proceso de entrevista.

📩 **Contact / Contacto:** cabrera.dev.rosano@gmail.com

## 📸 Project Showcase

**1. The Experience (Landing Page)**

A fully responsive, immersive UI built with **React**, **TypeScript**, and **Glassmorphism** aesthetics. Features real-time fundraising status tracking connected to the backend.

**2. Secure Administration (Web2)**

Protected Admin Panel using **JWT (JSON Web Tokens)** and **Bcrypt** for secure, stateless authentication. Designed for managing NFT metadata and "Real World Assets" (WildMe integration).

**3. The Dashboard & Web3 Integration**

The heart of the operations. Admins manage assets, while NFT owners can authenticate using **Wallet Signatures (SIWE - Sign In With Ethereum)** to prove ownership and modify their assets on-chain.

### 🛠 Technical Architecture

NFTAura is not just a frontend template. It is a robust **Full-Stack Application** engineered with security and scalability in mind.

**⚡ Backend (Node.js & Docker)**

* **Containerized Environment:** Fully orchestrated using **Docker Compose** and managed with **PM2-Runtime** for production resilience.

* **Hybrid Security Architecture**:

  * **Anti-Spoofing**: Webhook endpoints (for payments/donations) are secured using **HMAC SHA-256 signatures** to prevent tampering and replay attacks.

  * **Input Validation**: Strict schema validation using Zod to prevent injection attacks and ensure data integrity.

  * **Logging**: Structured asynchronous logging with **Winston** for security auditing.

* **Database**: **PostgreSQL** (running in Docker) with relational integrity for hybrid asset management.

**⚛️ Frontend (React & Web3)**

* **Tech Stack**: React, TypeScript, Vite.

* **Web3 Integration**: **Ethers.js** implementation for wallet connection and cryptographic message signing (verifying ownership without gas fees).

* **State Management**: React Context API for global authentication state (JWT).

* **Routing**: Protected routes (High-Order Components) to secure administrative areas.

* **i18n**: Full internationalization support (English/Spanish/French).
