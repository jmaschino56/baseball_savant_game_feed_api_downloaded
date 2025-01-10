# Baseball Savant Game Feed Scraper

## 📊 Overview

This Python package provides a `baseball_savant_game_feed_scraper` class designed to fetch and process game data from Baseball Savant. It utilizes the Baseball Savant API to retrieve game feeds and processes the data using `Polars` and `Pandas`. The scraper offers methods to clean, normalize, and compute advanced baseball metrics such as release positions, swing/whiff rates, and Magnus forces.

---

## 🚀 Features

- **Fetch Game Data**: Pulls game data from Baseball Savant using game IDs.
- **Normalize Data**: Adjusts pitch metrics for left-handed pitchers and normalizes plate and release metrics.
- **Advanced Metrics**:
  - Back-calculates release positions (`release_pos_x` and `release_pos_z`).
  - Calculates swing and whiff rates.
  - Computes aerodynamics like Magnus force and drag acceleration.
- **Attribute Enhancements**: Adds attributes for hand splits, normalized metrics, and advanced performance metrics.

---

## 🛠️ Requirements

- Python 3.8+
- Libraries:
  - `requests`
  - `polars`
  - `pandas`
  - `numpy`

### Install Dependencies
```bash
pip install requests polars pandas numpy
