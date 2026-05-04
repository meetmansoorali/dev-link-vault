# 🛠️ My.Toolbox
**A Minimalist, Non-Relational Link Management Utility**

<br>

![PHP](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat-square&logo=php&logoColor=white)
![Storage](https://img.shields.io/badge/Storage-JSON%20Flat--File-orange?style=flat-square)
![UI](https://img.shields.io/badge/UI-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

<br>

> **My.Toolbox** is a high-performance, portable web utility built for developers who need to organize local tools and documentation without the friction of a database system. 

<br>

## 👤 Developer
**Mansoor Ali** ([@meetmansoorali](https://github.com/meetmansoorali))
*Focusing on clean code, secure data handling, and minimalist design.*

<br>

## 📌 Project Overview
Modern development workflows require access to dozens of URLs, API endpoints, and local environments. This project replaces traditional browser bookmarks with a centralized, searchable dashboard.

Built with **Object-Oriented PHP (OOP)**, it emphasizes **Data Integrity** and **Zero-Config portability**.

<br>

## 🚀 Core Capabilities
*   **Zero-Dependency Storage:** Utilizes a JSON flat-file system for maximum portability.
*   **Security-Centric Design:** 
    *   **XSS Mitigation:** Comprehensive escaping via `htmlspecialchars()`.
    *   **Strict Sanitization:** URL filtering using `FILTER_SANITIZE_URL`.
*   **Instant Querying:** High-speed JavaScript DOM filtering for a real-time search experience.
*   **Responsive Architecture:** Optimized for a seamless experience from mobile to ultra-wide displays.

<br>

## 📂 System Architecture
```text
/my-toolbox
├── data/               # Persistent JSON storage (.gitignored)
├── src/
│   ├── Vault.php       # Core Engine: Encapsulates File I/O & Persistence
│   └── Link.php        # Entity Model: Handles Sanitization & Mapping
├── index.php           # Interface & Request Orchestration
└── README.md           # Documentation
