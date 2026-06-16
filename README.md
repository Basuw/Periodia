# 🗺️ Periodia — History step-by-step, map in hand.

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE.md)
[![Platform: iOS / Android](https://img.shields.io/badge/Platform-iOS%20%2F%20Android-blue.svg)](#)
[![Style: EdTech](https://img.shields.io/badge/Style-EdTech%20%2F%20Duolingo--like-green.svg)](#)

**Periodia** is an interactive mobile history learning application designed on the model of leading EdTech platforms (*Duolingo*, *Babbel*). The app allows users to explore the evolution of geopolitical borders through time, decipher milestone events directly on a dynamic map or via a country-by-country timeline, while anchoring their knowledge through gamified modules.

---

## 🚀 Key Features

### 📍 1. Temporal Mapping & Dynamic Borders
* **Geopolitical Time-Lapse:** Visually observe the expansion, contraction, and disappearance of empires, kingdoms, and nations across centuries.
* **Exploration by Country or Continent:** Filter the map on Europe or a specific country and scrub through time to watch borders shift live.

### 📖 2. Structured Learning via Chapters
* **Guided Journey:** History is no longer a dense, unreadable block. It is broken down into atomic, thematic, and chronological chapters (e.g., *Napoleonic Europe*, *Italian Unification*).
* **Event Cards:** Each micro-chapter contains a focus on "what happened", written in a clear, concise, and captivating storytelling format.

### 🏆 3. Retention by Design (Premium Reward System)
* **Validation Quizzes:** Test your comprehension at the end of each chapter to guarantee long-term retention.
* **The Profile Showcase:** Earn unique trophies (Imperial Seals, Coat of Arms, Golden Chronos) specific to each mastered historical period and proudly display them on your public showcase to challenge your peers.

### 👥 4. Social Learning & Ephemeris
* **Amigos System:** Add your friends, track their progress, compare your trophy showcases, and share striking historical facts directly with them.
* **"Today in the Past":** A daily routine presenting major events that occurred on today's date, but back in time.

---

## 🛠️ Technical Architecture

The application is built with a strict separation between the user interface and the temporal map rendering engine.

* **Frontend:** React Native — For a smooth, cross-platform mobile experience (iOS and Android) with an engaging, colorful UI.
* **Backend:** Spring Boot (Java) — A robust, scalable enterprise-grade framework to handle business logic, quiz validations, and user authentication.
* **Database:** PostgreSQL (with PostGIS extension) — Dedicated to storing transactional user data, social graphs ("Amigos"), and complex geohistorical vector data (temporal GeoJSON) for real-time border modifications.

---

## 🔒 License & Intellectual Property

⚠️ **All Rights Reserved.**

The source code, map data structures, educational content, graphic assets, and the overall concept of the **Periodia** application are protected by copyright law.

* **No authorized plagiarism or replication:** The code in this repository is shared solely for public viewing, code review, or portfolio demonstration purposes. Any unauthorized reproduction, modification, distribution, or commercial/non-commercial exploitation constitutes copyright infringement.
* For more detailed information, please refer to the `LICENSE.md` file.

---

## 📈 Roadmap

- [ ] V1.0 - MVP: Map of Europe from 1789 to present day + 10 major chapters + Basic quizzes.
- [ ] V1.1 - Social: Integration of the "Amigos" module, profile showcases, and friend comparisons.
- [ ] V1.2 - Ephemeris: Deployment of the daily "Today in the Past" feature.
- [ ] V2.0 - Global: Expansion of the temporal map to the entire world and introduction of 3D trophy showcases.