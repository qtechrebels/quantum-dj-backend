# quantum-dj-backend

![License: AGPL v3](https://img.shields.io/badge/license-AGPLv3-blue.svg)

A web application that leverages quantum-inspired optimization to generate dynamic music playlists based on user-selected seed tracks. Quantum DJ retrieves recommendations from [Last.fm](https://www.last.fm/) (© Last.fm), fetches 30-second previews via [Deezer](https://www.deezer.com/) (© Deezer), extracts audio features with Essentia (AGPL-3.0), and sequences the final playlist using OpenJij’s simulated annealing (Apache-2.0).

---

## Features

- **Seed-based Recommendations**: Enter three favorite tracks to start.
- **Last.fm Integration**: Fetch similar track suggestions via Last.fm API.
- **Deezer Previews**: Stream 30-second audio snippets directly in the browser.
- **Audio Feature Extraction**: Analyze BPM, key, spectral features, and more with Essentia.
- **Optimized Sequencing**: Formulate a QUBO model and solve via OpenJij to optimize the listening flow.

---

© 2025 Quantum DJ – A web application developed under the [QA4U3](https://altema.is.tohoku.ac.jp/QA4U3/) project.
