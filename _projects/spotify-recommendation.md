---
layout: single
title: "Spotify New Song Recommender"
permalink: /projects/spotify-recommendation/
excerpt: "Leveraged Spotifyʼs API data and ML pipelines to recommend new songs via a Streamlit app."
---

## Overview

Built a recommendation pipeline that surfaces new songs a user is likely to enjoy by combining Spotify API metadata with engineered features and machine learning.

**Key Results:**

- Featured a Streamlit demo for live recommendation exploration
- Validated model with precision, recall, and ranking metrics
- Trained on millions of streaming records pulled via Spotifyʼs Web API

**Tech Stack:** Python, pandas, scikit-learn, LightGBM, Spotify API, Streamlit, Plotly

**GitHub:** [View Code](https://github.com/hylin0517/spotify-new-song-recommender)
**Live Demo:** [Streamlit app](https://share.streamlit.io/example/spotify-new-song)

---

## The Problem

Spotify playlist owners wanted a way to surface new songs that aligned with their listening habits. The existing discovery process was too manual, and they needed a data-backed recommender.

---

## Approach

1. **Data Ingestion:** Pulled track, audio feature, and listening-history data from the Spotify API
2. **Feature Engineering:** Built user-song affinity features, rolling averages, and genre intensity indicators
3. **Modeling:** Trained ranking-aware gradient boosting models with LightGBM, tuning via cross-validation
4. **Evaluation:** Assessed precision@k, MAP@k, ROC AUC, and business KPIs from a holdout temporal split

---

## Key Findings

**Most impactful signals:**

- Recent streaming frequency and session duration
- Genre affinity and mood proximity
- Audio features (energy, danceability, valence)
- Collaborative similarity to curated playlists
- Artist popularity normalized by listening history

---

## Results

-- **Precision@10:** 72%
-- **MAP@10:** 0.65
-- **ROC AUC:** 0.89

The deployed recommender delivers new songs aligned with current user tendencies, enabling playlist creators to keep their listeners engaged.

---

## What I Learned

- Building Spotify API pipelines and authentication flows
- Engineering temporal and behavioral features for recommender signals
- Ranking-focused evaluation for consumer-facing predictions
- Deploying an interactive Streamlit interface for live exploration

---

[← Back to Projects](/projects/)
