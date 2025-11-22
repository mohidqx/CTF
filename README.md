# CyberØps CTF Platform
CyberØps CTF is a fully interactive Capture-the-Flag (CTF) platform featuring 700 handcrafted challenges across 7 major cybersecurity domains. Designed with a sleek, cyber-aesthetic interface and smooth UX, this platform is ideal for learning, training, and competitive CTF practice.

CyberØps provides everything you need in one place to sharpen your offensive security fundamentals and prepare for real-world competitions. This includes categories, difficulty tiers, points, filters, search functionality, progress tracking, and dynamic challenge popups.

## Table of Contents
1.  [Features](#features)
2.  [Challenge Structure](#challenge-structure)
3.  [Categories Overview](#categories-overview)
4.  [Tech Used](#tech-used)
5.  [Live Demo](#live-demo)
6.  [Future Additions](#future-additions)

## Features
*   🔥 **700 Total Challenges**
*   7 Categories × 100 challenges each

*   **Categories:**
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
*   Responsive design for all devices

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
*   XSS, SQLi, CSRF, SSRF, JWT attacks, file uploads, and more.

*   **Crypto**
*   Ciphers, hashing, RSA, XOR, ECB, padding oracles, and more.

*   **Forensics**
*   Files, memory, disks, stego, PCAPs, registries, and more.

*   **Reverse Engineering**
*   Binaries, APKs, obfuscation, custom VMs, anti-debug techniques, and more.

*   **Pwn**
*   Stack, heap, ROP, mitigations, kernel, sandbox escapes, and more.

*   **OSINT**
*   Geolocation, metadata, tracking, infrastructure analysis.

*   **Misc**
*   Puzzles, logic problems, programming challenges, games, math problems.

## Tech Used
*   HTML, CSS, JavaScript
*   Smooth animations
*   LocalStorage persistence
*   Responsive grid layout
*   Zero backend required

## Live Demo
Deployed on Vercel : [cyberops-ctf.vercel.app](https://cyberops-ctf.vercel.app)



## Future Additions
*   Leaderboards
*   User accounts
*   Real flag validation backend
*   Multiplayer competitions

## Credit
Made with ❤️ by [r00t:~#]
