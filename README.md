# Q-Learning sur MountainCar-v0

Projet AML – ESPRIT 4DAS · Encadrante : Wiem Trabelsi

**Équipe :** Kawther Amri · Balkiss Youssfi · Loussaif Bhiri · Manar Fares · Yasmine Maatougui · Khairi Charrad

Implémentation d'un agent **Q-Learning tabulaire** avec discrétisation des états sur l'environnement `MountainCar-v0` (Gymnasium).

Article de référence : *Modelling a Reinforcement Learning Agent For Mountain Car Problem Using Q-Learning With Tabular Discretization*, IEEE MysuruCon 2022. https://doi.org/10.1109/mysurucon55714.2022.9972352

## Avancement

| Phase | Contenu | Statut |
|---|---|---|
| 1 | Business Understanding | ✅ terminé |
| 2 | Data Acquisition & Understanding | ✅ terminé |
| 3 | Data Preparation : discrétisation des états | à venir |
| 4 | Modeling : Q-Learning, comparaison avec SARSA | à venir |
| 5 | Evaluation | à venir |

## Structure du dépôt

```
├── notebooks/
│   └── 01_Business_Understanding_Data_Acquisition.ipynb
├── data/              # transitions collectées (générées par le notebook)
├── results/figures/   # graphiques (générés par le notebook)
├── requirements.txt
└── README.md
```

## Installation

```bash
git clone <URL_DU_DEPOT>
cd AML-QLearning-MountainCar
pip install -r requirements.txt
```

## Exécution

```bash
jupyter notebook notebooks/01_Business_Understanding_Data_Acquisition.ipynb
```

Puis **Run → Run All Cells**. Les dossiers `data/` et `results/figures/` sont remplis automatiquement.

## Premiers résultats (phase 2)

| Politique | Récompense moyenne | Réussite |
|---|---|---|
| Agent aléatoire (baseline) | −200 | 0 % |
| Heuristique « suivre la vitesse » (repère) | −120 | 100 % |

20 000 transitions collectées, 11 contrôles de qualité validés.
