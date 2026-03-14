# Ibel Lagos | Dev & Security Portfolio

![Security](https://img.shields.io/badge/Security-Hardened-green?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-blue?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-Vanilla_JS-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-success?style=flat-square)

Minimalist professional portfolio built with a **security-first mindset**, optimized performance, and a hardened UI architecture.

🔗 **Live Demo:**
https://ibel-lagos.github.io/

---

# Overview

This project is a **static portfolio environment designed with security and minimal attack surface in mind**.

Instead of relying on modern frameworks, the site is intentionally implemented using **pure HTML, CSS, and Vanilla JavaScript**, reducing complexity and improving auditability.

Key principles:

* Security-by-design
* Zero external JavaScript dependencies
* Minimal attack surface
* Performance-first architecture

---

# Tech Stack

**Frontend**

* HTML5
* CSS3 (custom properties / design tokens)
* Vanilla JavaScript

**Typography**

* Plus Jakarta Sans
* Fraunces

**Environment**

* Static deployment (GitHub Pages)

---

# Security Hardening

This portfolio includes lightweight client-side hardening techniques commonly used in secure web environments.

### Security Headers

Implemented through meta tags:

* `X-Content-Type-Options: nosniff`
* `X-Frame-Options: DENY`
* `Referrer-Policy: no-referrer`

These help mitigate:

* MIME sniffing
* clickjacking
* unnecessary referrer leakage

---

### DOM Protection

Secure DOM manipulation strategy:

* Strict use of `textContent`
* Regex validation before rendering
* Avoidance of `innerHTML`

This significantly **reduces the risk of DOM-based XSS**.

---

### Anti-Scraping Measures

Contact information protection:

* Base64 encoded phone number
* Runtime decoding via JavaScript
* Randomized delay before external redirection

Purpose:

* reduce automated scraping
* reduce bot-based spam

---

### Tabnabbing Protection

All external links use:

rel="noopener noreferrer"

Mitigates **reverse tabnabbing attacks**.

---

# Performance

The site prioritizes **fast load times and minimal resource usage**.

Performance characteristics:

* Zero JavaScript frameworks
* No runtime libraries
* Minimal DOM manipulation
* Lightweight animations optimized for 60fps

This results in extremely fast rendering and low network overhead.

---

# Architecture

The project intentionally follows a **single-document architecture**.

```
portfolio
│
├── index.html
└── README.md
```

Benefits:

* easier auditing
* reduced complexity
* minimal dependency chain

---


# Professional Profile

Cybersecurity professional focused on building **technical tools and secure systems**.

My approach merges:

* modern development practices
* security engineering principles
* Linux-based environments

**Location:** Argentina

**Secure Contact:**
[ibeltech@protonmail.com](mailto:ibeltech@protonmail.com)

---

# License

This repository represents a **personal professional portfolio**.

You may use it for inspiration or educational purposes, but please avoid copying the project structure or design directly.
