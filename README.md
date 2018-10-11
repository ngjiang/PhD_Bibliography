# Plan de la biblio
## Phénomènes physiques
Problème de départ : Enceinte de confinement
Types de condensation : en film, en gouttes (et en masse ?) --> condensation en film 
Modèles existants : double analogie Chilton-Colburn, Bannwart, Kim, ..., Leduc (, ...) ([Leduc])
## Analogie HMTA
Hypothèses : équations, démonstrations, 
Utilisations : Chilton-Colburn ...
Critiques : vérification des hypothèses, résultats ...
## Modèles (Stratégies) CFD existants
### k-epsilon haut Reynolds (avec fonctions de paroi)
Différentes stratégies : FP + HMTA, 3 FPs indépendantes ...
Différentes FPs : (à interroger)
### k-epsilon bas Reynolds (maillage raffiné au voisinage du bord)
Pas de FP mais fonctions d'amortissement. Présentation des modèles
Existants : Launder-Sharma (OpenFOAM), Chien, Lam-Bremhorst, ...
HTMA pour les transferts thermique et massique
Q : impacté par les transferts thermique et massique ?
Notre approche : calculer k-epsilon bas-Reynolds avec le modèle bas-Mach avec l'interdiffusion Fourier-Fick et sortir des FP pour u, T, Yi


