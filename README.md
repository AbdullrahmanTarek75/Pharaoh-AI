<div align="center">

<img src="assets/logo.png" width="130" alt="Pharaoh-AI logo"/>

# 🇪🇬 Pharaoh-AI
### Egypt World Cup AI Lab
**AI-Powered Tactical Intelligence Platform for the Egyptian National Football Team**

*What if AI could help Egypt make smarter decisions throughout the FIFA World Cup?*

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)
![BLoC](https://img.shields.io/badge/State%20Management-flutter__bloc-blue)
![Hive](https://img.shields.io/badge/Offline%20Cache-Hive-yellow)
![Dio](https://img.shields.io/badge/Networking-Dio-green)
![License](https://img.shields.io/badge/License-MIT-success)

<img src="assets/screenshots/hero.png" alt="Pharaoh-AI — Tactical Pharaoh splash screen and AI Tactical Sanctuary chat" width="100%"/>

</div>

---

## 📑 Table of Contents

- [About the Project](#-about-the-project)
- [Application Modules](#-implemented-application-modules)
- [Screenshots](#-screenshots)
- [AI & Football Intelligence](#-ai--football-intelligence)
- [Main Screens](#-main-screens)
- [Architecture](#-architecture)
- [Tech Stack](#️-tech-stack)
- [Project Highlights](#-project-highlights)
- [Project Status](#-project-status)
- [Getting Started](#-getting-started)
- [Project Goal](#-project-goal)
- [Team & Academic Context](#-team--academic-context)

---

## 📖 About the Project

**Pharaoh-AI — Egypt World Cup AI Lab** is a football intelligence mobile application exploring how AI and data-driven analysis can support the Egyptian national team during a World Cup tournament.

The app brings match information, squad details, tactical reports, and prediction-oriented features into one interface. Its goal is to turn football data into clear summaries and decision-support insights for fans, coaches, and analysts.

The experience combines **Flutter mobile development**, **football analytics concepts**, **match and tournament views**, and an Egyptian-inspired visual identity.

<div align="center">

<img src="assets/screenshots/banner.png" alt="Pharaoh-AI — Your Tactical Edge" width="100%"/>

</div>

---

## 🚀 Implemented Application Modules

### 🏛 Harvest Chamber — Dashboard

The main dashboard brings key team and tournament information together.

- Qualification probability overview
- Next-match information and intelligence
- Tactical alerts and recommendations
- Squad readiness overview
- War Council Directive
- System synchronization status
- Offline cache support

### ⚔ Scrolls of Battle — Tournament Overview

A tournament and match intelligence section containing:

- Mission brief
- Battle intelligence
- Tactical reports
- Qualification status
- Match overview
- Tactical preview for upcoming matches

### 🏟 Match Command Center

A dedicated screen for reviewing match information and analysis.

- Match overview and statistics
- Tactical summary and insights
- Match timeline
- Possession information
- Expected Goals (xG) analysis
- Player ratings
- Heatmaps
- Preview mode for upcoming matches, based on available information

### 🔮 Oracle Engine — Predictions

A prediction-focused section for exploring possible tournament outcomes.

- Qualification probability
- Tournament progression
- World Cup bracket
- Scenario simulator
- Probability breakdown
- Oracle verdict
- Prediction metadata

### 🤖 AI Tactical Command Center

An interactive tactical assistant interface designed to support match preparation and football analysis.

- Tactical recommendations
- Formation suggestions
- Opponent analysis
- Match planning
- Risk assessment
- AI chat interface (Arabic and English)
- Command actions (generate match plan, predict final score, generate tactical report, generate locker-room speech)

### 👥 National Team Squad

A squad browsing and management interface featuring:

- Egypt national team squad
- Player position groups (goalkeepers, defenders, midfielders, forwards)
- Player details
- Injury reports and availability status
- Search and filtering
- Squad statistics

---

## 📷 Screenshots

### Dashboard, War Council & Squad Details

Harvest Chamber with qualification probability and squad overview · War Council with key battlefronts, risk diagnostic monitor and AI command actions · player profile with availability and injury report · next-match countdown with the Solar Disk Destiny gauge.

<div align="center">
<img src="assets/screenshots/dashboard_war_council.png" alt="Dashboard, War Council, player details, and next match countdown" width="100%"/>
</div>

### Squad Search, Oracle Scenario Simulator & Match Command Center

Squad search and filters · Oracle Engine scenario simulator and group standings · Match Command Center with countdown, venue, qualification destiny and War Council directive · position-grouped squad list.

<div align="center">
<img src="assets/screenshots/squad_oracle_match.png" alt="Squad search, Oracle scenario simulator, Match Command Center, and squad list" width="100%"/>
</div>

### Qualification Status, World Cup Bracket & Probability Breakdown

Scrolls of Battle projection probabilities · Round of 32 bracket views · tournament path and probability breakdown from group stage to champion.

<div align="center">
<img src="assets/screenshots/oracle_bracket.png" alt="Qualification status, World Cup bracket, tournament path, and probability breakdown" width="100%"/>
</div>

> Probabilities and match data shown in the screenshots are model outputs from a development build and are illustrative of the app's features.

---

## 🧠 AI & Football Intelligence

The project explores AI-assisted football analysis through features such as:

- Tactical recommendations and match insights
- Opponent analysis and match planning
- Qualification and tournament-outcome predictions
- Scenario-based simulations
- Dynamic tactical reports
- AI-assisted coaching interactions

These features are intended to support human analysis and decision-making, not replace it. Predictions and recommendations should be interpreted in the context of the data available to the application.

---

## 📱 Main Screens

- Splash and onboarding
- Dashboard (Harvest Chamber)
- Scrolls of Battle
- Match Command Center
- Oracle Engine
- AI Tactical Command Center (War Council)
- National Team Squad
- Chat Assistant (Tactical Sanctuary)

---

## 🏗 Architecture

The app is organized around a **Clean Architecture** approach, separating presentation and business logic from data access.

```text
Presentation
    │
    ▼
Cubit / BLoC
    │
    ▼
Repository
    │
    ▼
Datasource
    │
    ▼
REST API
```

### Project Structure

```text
lib/
├── core/
├── features/
│   ├── dashboard/
│   ├── match_analysis/
│   ├── predictor/
│   ├── ai_coach/
│   ├── squad/
│   ├── chat/
│   ├── splash/
│   └── onboarding/
└── main.dart
```

---

## ⚙️ Tech Stack

| Area | Technologies |
|---|---|
| Mobile application | Flutter, Dart |
| Architecture | Clean Architecture, Repository Pattern |
| State management | `flutter_bloc` |
| Networking | Dio |
| Local/offline storage | Hive |
| Navigation | GoRouter |
| Backend communication | REST APIs |

---

## ✨ Project Highlights

- Egyptian and Pharaonic-inspired user interface
- Modular feature-based code structure
- BLoC/Cubit-based state management
- REST API integration through Dio
- Offline caching support with Hive
- Match analysis and tournament prediction screens
- Squad browsing and filtering
- Tactical assistant interface
- Interactive football intelligence experience

---

## 📊 Project Status

- [x] Dashboard
- [x] Match Center
- [x] Oracle Engine
- [x] AI Coach
- [x] Squad module
- [x] Tactical Reports
- [ ] Continuous improvements and refinements

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.x)
- Dart SDK (3.x)
- An editor such as Android Studio or Visual Studio Code

### Installation

Clone the repository:

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_PROJECT_DIRECTORY>
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

> Replace the repository URL and project directory with the actual values for your GitHub repository.

---

## 🎯 Project Goal

Pharaoh-AI explores how football data, prediction tools, and AI-assisted analysis can help people understand matches and evaluate tactical options. The application brings these ideas together in a mobile experience focused on the Egyptian national team.

---

## 👨‍💻 Team & Academic Context

Developed as a graduation project at:

**Faculty of Engineering — Shoubra**  
**Benha University**  
Computer and Communication Engineering

---

<div align="center">

### 🇪🇬 Made with ❤️ for Egyptian Football

</div>
