---
title: "Spotify New Song Recommender"
permalink: /projects/spotify-recommendation/
---

## Overview

Built a recommendation pipeline that surfaces new songs a user is likely to enjoy by combining Spotify API metadata with engineered features and machine learning.
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


[← Back to Projects](/projects/)
