# 🏊 SwimMetrics — Ultimate Aquatic Intelligence

> **🏆 Winner — Best Application of Design Thinking**
> Hackathon in collaboration with **Aquatics GB** · University of Sheffield

SwimMetrics is a full-stack data analytics platform built for elite swimming coaches, performance analysts, and national federations. It transforms raw competitive swim data into actionable intelligence — surfacing global talent, projecting Olympic readiness, and benchmarking athletes against the world's best.

---

## 📽️ Demo

### 1 · Landing & Global Overview
![SwimMetrics Hero & Global Dominance Map](assets/01_landing_hero.gif)

*The hero landing leads into a live globe visualisation of **100m Freestyle global dominance** by country, paired with an **Evolution of Elite** line chart tracing how gold-medal pace has changed from 2000 to 2025.*

---

### 2 · Global Leaderboard & Smart Filtering
![Leaderboard and Filters](assets/02_leaderboard_filters.gif)

*A **Quick Athlete Search** across 22,000+ athletes feeds into a fully filterable **Global Leaderboard**. Coaches can slice by gender, country, stroke (Freestyle / Backstroke / Breaststroke / Butterfly / IM), distance, and timeframe — instantly. Summary cards surface the **leader pace**, **top-8 cutoff**, and **average gap to gold** at a glance.*

---

### 3 · Progression Analytics — Career Intelligence
![Progression Analytics](assets/03_progression_analytics.gif)

*Selecting any athlete loads their **Career Intelligence Timeline** — a trendline with projection confidence bands, personal-best highlights, and a short-term forecast. Scrolling further reveals a **Performance & Context** breakdown: career stage, years competing, gap to the global top-10, and a cross-country contextual chart. The section closes with an **LA 2028 Olympic Projection** — a baseline predicted time, a forecasted outcome label (e.g. "Podium Contender"), and a **Projected Placement Zone** chart showing where the athlete sits relative to gold, bronze, and finalist pace.*

---

### 4 · Comparator Dashboard — Athlete Matching & Scouting
![Comparator Dashboard](assets/04_comparator_dashboard.gif)

*The Comparator uses a **Match Engine** to find the 10 closest global peers to any athlete — comparing trajectory, consistency, and best time. A **Global Distribution of Peers** heatmap reveals which nations are producing the most direct competition, accompanied by an AI-generated **Scouting Insight**. The view closes with a **Career Trajectory Comparison** chart overlaying all matched athletes across years.*

---

## ✨ Features at a Glance

| Feature | Description |
|---|---|
| 🌍 Global Dominance Globe | Interactive 3D map of country-level performance in any event |
| 📈 Evolution of Elite | Historical gold-medal pace trend from 2000–2025 |
| 🔍 Quick Athlete Search | Instant fuzzy search across 22,000+ international athletes |
| 🏅 Global Leaderboard | Filterable ranking by gender, country, stroke, distance & era |
| 📊 Career Intelligence Timeline | Personal trendlines, PB highlights, & projection confidence bands |
| 🎯 LA 2028 Olympic Projection | AI-driven placement zone predictions with gold/bronze/finalist targets |
| 🤝 Athlete Comparator | ML-based peer matching by trajectory + consistency + pace |
| 🗺️ Peer Distribution Map | Geographic heatmap of where competition is concentrated |
| 💡 AI Scouting Insight | Plain-English coaching takeaways generated per athlete |

---

## 🏗️ Architecture & Tech Stack

```
SwimMetrics
├── Frontend        React + Plotly.js + Leaflet (globe visualisation)
├── Data Layer      Custom ETL pipeline — FINA/World Aquatics results data
├── Analytics       Python (Pandas, Scikit-learn) — projection & matching models
└── Design System   Dark-mode-first UI with a Navy / Cyan / Gold palette
```

---

## 🎨 Design Thinking Approach

The hackathon brief required us to apply **design thinking methodology** end-to-end. Our process:

1. **Empathise** — Interviewed Aquatics GB performance analysts to understand pain points: data was scattered, comparisons manual, Olympic readiness hard to quantify.
2. **Define** — Core problem: *"Coaches lack a single, intelligent view of where an athlete stands globally and where they're headed."*
3. **Ideate** — Ran rapid sketching sessions across three personas: Head Coach, Talent Scout, and National Performance Director.
4. **Prototype** — Built three iterative prototypes, refining the information hierarchy each round based on coach feedback.
5. **Test** — Validated with Aquatics GB stakeholders; adjusted LA 2028 projection visualisation after feedback that raw numbers without context were misleading.

---

## 🤝 Collaboration

This project was developed in partnership with **Aquatics GB** as part of a hackathon hosted at the **University of Sheffield**. We worked alongside GB performance staff to ensure the analytics reflected real coaching workflows rather than theoretical dashboards.

---

## 🏆 Recognition

> **🥇 Best Application of Design Thinking** — University of Sheffield Hackathon × Aquatics GB

---

## 📁 Repository Structure

```
swimmetrics/
├── src/
│   ├── components/        # React UI components
│   ├── pages/             # Home · Progression Analytics · Comparator
│   ├── data/              # ETL scripts and processed datasets
│   └── models/            # Projection & peer-matching algorithms
├── public/
├── assets/                # GIFs and screenshots for this README
└── README.md
```

---

*Built with 💙 at the University of Sheffield · Powered by World Aquatics data*
