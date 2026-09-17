Computer and Information Technology graduate from Politehnica University of Bucharest, previously interning as a Software Development Intern (Data Engineering & GIS) at ICI Bucharest. I build across full-stack systems, distributed and networked systems, and mobile apps — with some detours into GPU programming and embedded hardware.

![Open to Work](https://img.shields.io/badge/Open%20to-Work-2ea44f?style=flat-square)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mahmoudimohammadmehdi50@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/M-Mehdi-M)

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

- Encrypted every entry with AES-256-GCM via hardware-backed Android Keystore, with a unique IV per entry.
- Built a panic-password flow that swaps the vault for a decoy calculator screen, with an optional auto-destruct wipe.

`Kotlin` `Android` `Security`

**Other Projects**
- [SpendScan](https://github.com/M-Mehdi-M/SpendScan) — Android expense tracker using ML Kit OCR to scan receipts and auto-categorize spending. `Java` `Android`
- Parallel News Aggregator — Multithreaded Java pipeline (parse → dedupe → stats → write), synchronized across phases with a CyclicBarrier. `Java` `Concurrency`
- Sound Classification — Gabor and custom wavelet filter banks on the Mel scale for audio feature extraction, feeding KNN/nearest-centroid classifiers, reaching up to 68% accuracy across four classifier/filter combinations. `Python` `Signal Processing`
- Mini-libc — A freestanding C standard library implementation on raw Linux syscalls (strings, memory, POSIX I/O). `C` `Linux`
- [CUDA Proof-of-Work Miner](https://github.com/M-Mehdi-M/2-cuda_proof_of_work) — GPU-parallelized Merkle tree construction and nonce search for a simplified blockchain miner. `CUDA` `C++`
- TCP/UDP Message Broker — Pub/sub broker with wildcard topic matching over TCP subscriptions and UDP publishing. `C` `Sockets`
- EbookReader — ESP32-C6 e-paper reader board: full schematic, PCB routing, and BOM. `Embedded` `PCB Design`

---

## Technical Skills

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/-C-555555?style=flat-square)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Systems & Networking**
![MPI](https://img.shields.io/badge/-MPI-4B0082?style=flat-square)
![Sockets](https://img.shields.io/badge/-Sockets-2E8B57?style=flat-square)
![Multithreading](https://img.shields.io/badge/-Multithreading-555555?style=flat-square)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Mobile & Web**
![Android](https://img.shields.io/badge/-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/-REST%20APIs-FF6C37?style=flat-square)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Data & ML**
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat-square)
![Folium](https://img.shields.io/badge/-Folium-77B829?style=flat-square)

**Tools**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Education

**B.Eng. in Computer and Information Technology**
Politehnica University of Bucharest — Faculty of Automatic Control and Computer Science
*2022 – 2026*
