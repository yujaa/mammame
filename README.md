# 🍽 Mammame: Pregnancy Food Safety Search (Korean Web)

<p align="center">
  <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge" alt="Live">
  <img src="https://img.shields.io/badge/Platform-Web-green?style=for-the-badge" alt="Web">
  <img src="https://img.shields.io/badge/UI-Korean-orange?style=for-the-badge" alt="Korean UI">
  <img src="https://img.shields.io/badge/Compose-Multiplatform-blue?style=for-the-badge" alt="Compose Multiplatform">
  <img src="https://img.shields.io/badge/Language-Kotlin-purple?style=for-the-badge" alt="Kotlin">
</p>

**Mammame** is a **live, production-running web application** that helps pregnant users
search and compare food safety information using **Korean-language sources**.

The service is implemented in **Kotlin using Compose Multiplatform (Web)** and
compiled to JavaScript for browser execution.
It aggregates food safety guidance from multiple public sources and presents
them in a structured, reliability-aware format.

> ✅ This repository hosts the **actively running Korean web version** of Mammame.

---

## 🌐 Live Website

👉 **https://mammame.app**  
*(Korean-language web application, currently in operation)*

---

## 🌟 Key Features

- **Food-Centered Search**  
  Search pregnancy-related food safety information by food name (Korean).

- **Multi-Source Comparison**  
  Aggregates guidance from medical institutions, governmental sources,
  corporate publications, and community references.

- **Reliability-Aware Summaries**  
  Groups sources by credibility level (high / medium / low) to highlight
  dominant opinions and disagreements.

- **Verdict-Based Filtering**  
  Filter sources by verdict:
  - Safe
  - Conditional
  - Caution
  - Avoid

- **Responsive Web UI**  
  Optimized for both mobile and desktop browsers.

---

## ⚙️ How It Works

1. Users search for a food item by name.
2. The query is matched against a curated CSV-based dataset.
3. Entries are deduplicated by source and normalized by verdict.
4. Sources are grouped and ranked by reliability.
5. Results are displayed with filters and direct source links.

---

## 🛠 Tech Stack

### Language
- Kotlin

### Framework
- Compose Multiplatform (Web)
  - Kotlin code is **compiled to JavaScript** and runs directly in the browser.

### Data
- CSV-based ingestion
- Client-side parsing, ranking, and filtering

### UI
- Responsive layout
- Reliability indicators
- Source-level external links

---

## ⚠️ Disclaimer

Mammame does **not** provide medical advice.

All information presented in this application is aggregated from publicly
available sources for general reference purposes only.
Pregnancy-related food safety decisions should always be made in consultation
with qualified healthcare professionals.

---

## 📜 License & Attribution

This project was initially bootstrapped from the  
[JetBrains Compose Multiplatform Template](https://github.com/JetBrains/compose-multiplatform-template),  
which is licensed under the **Apache License 2.0**.

Significant modifications and original implementation have been added on top
of the template.

---

## 🚧 Project Status

This project is **actively running and maintained**.

- Data sources may expand or change
- UI and ranking logic may evolve
- No guarantees are made regarding completeness or correctness

An English UI version with AI-assisted features is developed separately.

---

## 📬 Contact

Questions, feedback, or collaboration ideas are welcome.

📧 **mammame.app@gmail.com**
