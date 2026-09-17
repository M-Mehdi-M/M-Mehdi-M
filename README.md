Computer and Information Technology graduate from Politehnica University of Bucharest, previously interning as a Software Development Intern (Data Engineering & GIS) at ICI Bucharest. I build across full-stack systems, distributed and networked systems, and mobile apps — with some detours into GPU programming and embedded hardware. I care about repos that are easy to pick up — clear READMEs, sensible structure, code that explains itself.

---

## Relevant Projects

### [SmartPermits](https://github.com/M-Mehdi-M/SmartPermits)
*A full-stack Android + Flask platform that digitizes municipal permit workflows, from application to inspection to certificate issuance.*

- Built role-based citizen/inspector dashboards on JWT auth, with real-time status updates over Socket.IO.
- Integrated Google Gemini for automated document verification against permit requirements, and Ethereum Sepolia for hash-anchored permit notarization.
- Generated government-style PDF certificates with embedded QR codes linking to the on-chain verification record.

`Java` `Android` `Flask` `SQLite`

### CHORD Protocol in MPI
*A simplified CHORD distributed hash table where nodes locate keys in logarithmic hops instead of linear search, built on MPI message passing.*

- Implemented finger-table construction and closest-preceding-finger routing so every hop provably makes progress toward the target key around the ring.
- Handled asynchronous lookup forwarding across all nodes with a tag-based service loop (request / reply / done), so idle nodes keep routing others' lookups until the whole ring finishes.

`C` `MPI` `Distributed Systems`

### IPv4 Router Implementation
*A software IPv4 router handling forwarding, ARP, and ICMP over raw sockets.*

- Built longest-prefix-match routing on a bit-trie constructed once at startup, replacing linear route search with logarithmic-depth lookups.
- Implemented ARP request/reply handling with a queue for packets awaiting address resolution, and generated ICMP Time Exceeded / Destination Unreachable replies.

`C` `Networking` `Sockets`

### [SafeVault](https://github.com/M-Mehdi-M/SafeVault)
*An Android vault app for encrypting sensitive data, with a document scanner and duress features.*

- Encrypts every entry with AES-256-GCM via hardware-backed Android Keystore, with a unique IV per entry.
- Built a panic-password flow that swaps the vault for a decoy calculator screen, with an optional auto-destruct wipe.

`Kotlin` `Android` `Security`

**Other Projects**
- [SpendScan](https://github.com/M-Mehdi-M/SpendScan) — Android expense tracker using ML Kit OCR to scan receipts and auto-categorize spending. `Java` `Android`
- Parallel News Aggregator — Multithreaded Java pipeline (parse → dedupe → stats → write), synchronized across phases with a CyclicBarrier. `Java` `Concurrency`
- Sound Classification — Gabor and custom wavelet filter banks on the Mel scale for audio feature extraction, feeding KNN/nearest-centroid classifiers. `Python` `Signal Processing`
- Mini-libc — A freestanding C standard library implementation on raw Linux syscalls (strings, memory, POSIX I/O). `C` `Linux`
- [CUDA Proof-of-Work Miner](https://github.com/M-Mehdi-M/2-cuda_proof_of_work) — GPU-parallelized Merkle tree construction and nonce search for a simplified blockchain miner. `CUDA` `C++`
- TCP/UDP Message Broker — Pub/sub broker with wildcard topic matching over TCP subscriptions and UDP publishing. `C` `Sockets`
- EbookReader — ESP32-C6 e-paper reader board: full schematic, PCB routing, and BOM. `Embedded` `PCB Design`

---

## Technical Skills

| Category | Details |
| :--- | :--- |
| **Languages** | Python · Java · C · C++ · Kotlin |
| **Systems & Networking** | MPI · Sockets · Multithreading · CUDA |
| **Mobile & Web** | Android SDK · Flask · REST APIs · HTML/CSS |
| **Data & ML** | Pandas · GeoPandas · NumPy · SciPy · scikit-learn · Folium |
| **Tools** | Docker · Git/GitHub · Linux |

---

## Education

**B.Eng. in Computer and Information Technology**
Politehnica University of Bucharest — Faculty of Automatic Control and Computer Science
*2022 – 2026*
