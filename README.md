# EidP-DrugDiscovery

Introductory ML project for *Einführung in die Programmierung (EidP)*. We work with the BACE-1 dataset and predict whether molecules inhibit the BACE-1 enzyme using a neural network.

## Notebook öffnen

### Option 1: Google Colab (im Browser, ohne Installation)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haagjjan/EidP-DrugDiscovery/blob/main/W1-bace_drug_discovery_studierende.ipynb)

1. Auf den Button oben klicken (oder direkt öffnen: `https://colab.research.google.com/github/haagjjan/EidP-DrugDiscovery/blob/main/W1-bace_drug_discovery_studierende.ipynb`).
2. Über **File → Save a copy in Drive** eine eigene Kopie speichern, damit Änderungen erhalten bleiben.

### Option 2: JupyterHub / lokales Jupyter Notebook

1. `W1-bace_drug_discovery_studierende.ipynb` herunterladen (auf GitHub anklicken → **Download raw file**) oder das Repository klonen:
   ```bash
   git clone https://github.com/haagjjan/EidP-DrugDiscovery.git
   ```
2. Die Datei auf **JupyterHub** hochladen (bzw. lokal mit `jupyter notebook` oder VS Code öffnen).
3. Die Zellen von oben nach unten ausführen. `bace.csv` wird automatisch erstellt; falls `scikit-learn` fehlt, installiert Zelle 1 es automatisch.
