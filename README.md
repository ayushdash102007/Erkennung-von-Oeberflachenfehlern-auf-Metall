# Erkennung-von-Öberflachenfehlern-auf-Metall
## Überblick 
Dieses Projekt verwendet Methoden des Deep Learnings, um Öberflachenfehlern auf Metall zu erkennen. 
## Verwendete Python Bibliotheken 
- Tensorflow
- Numpy
- Matplotlib (für Graphen)
## ML-Pipleline
```mermaid
flowchart TD
    A([Start]) --> B[Load Dataset]
    B --> C[Preprocess Images]
    C --> D[Split Dataset]
    D --> E[Build CNN]
    E --> F[Train Model]
    F --> G[Validate Model]
    G --> H{Performance Satisfactory?}
    H -- No --> I[Hyperparameter Tuning]
    I --> F
    H -- Yes --> J[Test Model]
    J --> K[Save Model]
    K --> L[Predict New Images]
    L --> M([End])
```
