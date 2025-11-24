---
title: Projects
layout: collection
permalink: /projects/
collection: projects
entries_layout: grid
author_profile: true
classes: wide
---

## [Spotify New Song Recommender](/projects/spotify-recommendation/)
- **Goal:** Surface new tracks that align with a user’s listening habits using Spotify metadata and behavior.
- **Approach:** Ingested Spotify API data, engineered affinity and genre metrics, trained ranking-aware LightGBM, and validated via temporal holdouts with precision@k and MAP@k.
- **Result:** Precision@10 of 72% and MAP@10 of 0.65 in cross-validated splits, plus an interactive Streamlit demo that recommends live songs.
- **Stack:** Python, pandas, LightGBM, Spotify API, Streamlit, Plotly.
- **Links:** [Case study](/projects/customer-churn-prediction/) · [GitHub repo](https://github.com/hylin0517/spotify-new-song-recommender)

---

## More work coming soon
- Building out additional projects on recommendation, forecasting, and experimentation.
