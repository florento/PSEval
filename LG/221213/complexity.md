







### Complexité: 
(calcul de plus court chemin)

(nb configurations):
dans le cas le pire:
exponentielle dans la longueur d'1 mesure

- [ ] borne inf. ?



exemple LG #470
cf. `debugpse.cpp`

la mesure 9 est un cas extreme:
- 30 notes
- beaucoup de chromatismes (presque une alteration par note)

à l'initialisation de la table (calcul des best-path),
extraction min cost d'une file d'attente
-> exploration quasi en largeur d'abord sur cet exemple
-> explosion exponentielle

- [ ] essayer de laisser tourner 470?
- [ ] option sans les ## et bb ?
- [ ] comparer 470 avec autres outils ?
- [ ] autres cas similaires apres 470?


