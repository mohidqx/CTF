# CyberØps CTF Platform
CyberØps CTF is a fully interactive Capture-the-Flag (CTF) platform. It features 700 handcrafted challenges spanning 7 major cybersecurity domains. Designed with a sleek cyber-aesthetic interface and smooth UX, this platform is ideal for learning, training, and competitive CTF practice.

CyberØps provides everything you need in one place to sharpen your offensive security fundamentals or prepare for real-world competitions. This includes categories, difficulty tiers, points, filters, search, progress tracking, and dynamic challenge popups.



## Features
*   🔥 **700 Total Challenges**
*   7 Categories × 100 challenges each

*   **Web**
*   **Crypto**
*   **Forensics**
*   **Reverse Engineering**
*   **Misc**
*   **Pwn**
*   **OSINT**

*   🎚️ **Difficulty Levels**
*   33 Easy
*   33 Normal
*   33 Hard
*   1 Legendary

*   🏆 **Progress Tracking**
*   Solved counter per category
*   Total points counter
*   LocalStorage-based persistent progress

*   🔍 **Smart Filters & Search**
*   Filter by category
*   Filter by difficulty
*   Real-time search box

*   🚀 **Challenge Modal**

Each challenge includes:

*   Title, ID, category, difficulty
*   Description
*   Challenge path
*   Flag submission box
*   Points system
*   Animated premium-style modal UI

*   💻 **Built-in Matrix Theme**
*   Dynamic falling code
*   Animated glowing UI
*   Gradient effects
*   Responsive for all devices



## Challenge Structure
Each challenge follows a consistent folder pattern:

```
ctf/<category>/<difficulty>/<id>/
```

Flags follow a simple, predictable format for testing:

```
FLAG{category_difficulty_id}
```



## Categories Overview
*   **Web**
*   XSS, SQLi, CSRF, SSRF, JWT attacks, file uploads, etc.

*   **Crypto**
*   Ciphers, hashing, RSA, XOR, ECB, padding oracles, etc.

*   **Forensics**
*   Files, memory, disks, stego, PCAPs, registries, etc.

*   **Reverse Engineering**
*   Binaries, APKs, obfuscation, custom VMs, anti-debug, etc.

*   **Pwn**
*   Stack, heap, ROP, mitigations, kernel, sandbox, etc.

*   **OSINT**
*   Geolocation, metadata, tracking, infrastructure analysis.

*   **Misc**
*   Puzzles, logic, programming, games, math.



## Tech Used
*   HTML, CSS, JavaScript
*   Smooth animations
*   LocalStorage persistence
*   Responsive grid layout
*   Zero backend required



## Live Demo
You can host this anywhere (GitHub Pages, Vercel, Netlify). Simply drop the repo as-is, and it works instantly.



## Future Additions
*   Leaderboards
*   User accounts
*   Real flag validation backend
*   Multiplayer competitions
