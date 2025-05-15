# 🎵 Music Genre Classifier App

![App UI Screenshot](https://github.com/user-attachments/assets/68c21b6b-47c1-4e1f-b04b-65b6620115bd)

## Overview

The **Music Genre Classifier App** is a MATLAB App Designer tool that lets you load any WAV file and instantly predict its musical genre using a pre-trained machine-learning model. No coding required—just point, click, and listen!

## Supported Genres

This app can classify into these ten popular genres (from the GTZAN dataset):

- **Blues**  
- **Classical**  
- **Country**  
- **Disco**  
- **Hip-Hop**  
- **Jazz**  
- **Metal**  
- **Pop**  
- **Reggae**  
- **Rock**  

## Dataset

We built and evaluated our model on the **GTZAN Music Genre** dataset, which contains 1 000 excerpts (30 s each) evenly distributed across the 10 genres above.  
> **Reference:** M. Tzanetakis and P. Cook, “Musical Genre Classification of Audio Signals,” *IEEE Trans. Speech Audio Process.*, vol. 10, no. 5, pp. 293–302, Jul. 2002.

## Requirements

- **MATLAB R2021a** or later  
- **Signal Processing Toolbox**  
- **Statistics and Machine Learning Toolbox**  

## How to Use

1. Open **MusicGenreClassifierApp.mlapp** in MATLAB App Designer.  
2. Click **Run ▶** to launch the GUI.  
3. In the app window:  
   - Hit **Load Audio** and select your WAV file.  
   - Press **Classify** to display the predicted genre and confidence score.  
   - (Optional) Browse the built-in recommendations for similar tracks.  

## File Structure


```

├── MusicGenreClassifierApp.mlapp   # Main App file
├── models/                         # Pre-trained .mat model
├── data/                           # Example WAV files (optional)
└── docs/
└── images/
└── gui\_screenshot.png      # UI screenshot used above

```

## 🤝 Contributors

* [@canomercik](https://github.com/canomercik) – GUI design & optimization
* [@mustafayngl](https://github.com/mustafayngl) – Feature extraction & model training
* [Riad Memmedli](https://github.com/riadmmdli) – Report & visualization

---

## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

```
```

