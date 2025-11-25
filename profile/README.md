# Block-Xaero

**Powering Offline-First, Decentralized and fast Collaboration through offline-first libraries and Apps**

Block-Xaero is building the foundational  local-first infrastructure for truly decentralized applications that work without the cloud. Our technology stack enables native apps with peer-to-peer collaboration with focus on efficiency and privacy. 

---

## Our Vision

**Decentralized. Offline-First. User-Owned.**

We're creating a world where:
- Your data stays on your devices, not corporate servers
- AI models learn collaboratively without centralized training
- Applications work seamlessly offline and sync peer-to-peer
- Cryptographic proofs ensure trust without intermediaries
- Native performance rivals cloud-based solutions

---

## Technology Stack
**UI**: We use Swift and Flutter for UI
**Backend:** Our Backend is mostly local first built on Rust with tokio and candle-rs.
**AI models:** PyTorch and Candle-rs - quantized and local, we use MIT or Apache licensed models.

## Xaeroflux
Event store that synchronizes with peers via QUIC built on Rust and Iroh.

## XaeroID
did:peer SSI identity combined with ZK Proofs



## Flagship Application: Cyan
Cyan is our offline-first design and collaboration social network built to scale without mostly no cloud infrastructure. It is a collaboration social network built to serve as knowledgeware-house but in a fun collaborative way. Think of slack + confluence + pinterest in intra-business - b2b world.

### Technical Architecture

```
Cyan App Architecture
├── Swift / Flutter
├── Rust Backend (FFI)
   ├── Cyan Backend
   ├── Cyan Integrations (Slack, JIRA, Confluence and much more) - bridging the other tool collaboration gap in a meaningful way.
   ├── XaeroFlux (Event Sync using QUIC)
   └── XaeroAI (On-device Inference)
```

---


## Getting Started

### For Developers

```bash
# Clone the ecosystem
git clone https://github.com/block-xaero/cyan-ios.git
git clone https://github.com/block-xaero/cyan-backend.git
git clone https://github.com/block-xaero/cyan-backend-integrations.git
git clone https://github.com/block-xaero/xaeroflux.git
git clone https://github.com/block-xaero/xaeroid.git  
git clone https://github.com/block-xaero/xaeroai.git

# Build the stack
cd xaeroflux && cargo build
cd ../xaeroid && cargo build  
cd ../xaeroai && cargo build
```

### For Enterprises
Contact us at: heejee.jo@blockxaero.io or anirudh.vyas@blockxaero.io for a demo of how Cyan can help you.



## Join the Decentralized Future
Block-Xaero is more than technology—it's a movement toward user-owned, privacy-preserving applications that work without Cloud infrastructure needs.

### **Community**
- **Website:** [blockxaero.io](https://blockxaero.io)
- **Discord:** [discord.gg/pDy2hu7X](https://discord.gg/pDy2hu7X)
- **GitHub:** [github.com/block-xaero](https://github.com/block-xaero)

