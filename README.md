# Secure Portfolio Landing Page

A high-performance, responsive landing page developed with a **Security-First** mindset. This project serves as a professional showcase for technical services, integrating defensive programming techniques to mitigate common web vulnerabilities.

## 🛡️ Security Implementation (Hardening)

This project implements several security layers to ensure code integrity and user privacy:

* **XSS Mitigation:** Strict use of `textContent` instead of `innerHTML` to prevent Cross-Site Scripting.
* **Input Sanitization:** Regex-based validation for all dynamic content and localization strings.
* **Security Headers:** Meta-tag implementation for `X-Content-Type-Options`, `X-Frame-Options` (Clickjacking protection), and `Referrer-Policy`.
* **Contact Obfuscation:** Dynamic construction of contact links to prevent automated scraping and spam bots.
* **Secure Navigation:** Applied `noopener` and `noreferrer` to all external links to prevent Tabnabbing attacks.
* **Logic Encapsulation:** Entire logic wrapped in an IIFE to protect the global scope and maintain execution integrity.

## 🚀 Technologies

* **Language:** Vanilla JavaScript (ES6+)
* **Styling:** CSS3 with Custom Properties and Hardware-accelerated animations.
* **Architecture:** Zero-dependency, purely client-side.
* **Typography:** Optimized loading of Google Fonts (Fraunces & Plus Jakarta Sans).

## 🛠️ Features

* **Dual Language Support:** Integrated localization (ES/EN) with secure state management.
* **Dynamic UI:** Custom progress bar, glassmorphism header, and interactive background orbs.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewports.
* **Accessibility:** ARIA labels and semantic HTML structure.

## 📋 License

This project is for personal use and portfolio demonstration. Feel free to explore the security implementations.

---
Developed by [Ibel Lagos](https://github.com/ibel-lagos).
