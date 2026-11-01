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
    A([Beginn]) --> B[Laden des Datasatzen]
    B --> C[Vorverarbeitung von Bildern Normalisierung]
    C --> D[Aufbau des CNN Modells]
    D --> E[Training des Modells]
    E --> F[Validierung des Modells]
    F --> G{Zufriedenheit mit dem Modell}
    G --> H([End])
```
