# PS eval: ASAP dataset, Bach
evaluation of Wohltemperierte Clavier, Preludes & Fugues

excluded (cause of complexity explosion):
- BWV 856, Prelude
- BWV 873, Prelude

27 fev 2023
version PSE: v0.6
PSeval with 25 tonalities: 
- major KS -4 to 7 : C, C#, D, Eb, E, F, F#, G, Ab, A, Bb, B
- minor harm KS -6 to 6 : C, C#, D, Eb, D#, E, F, F#, G, G#, A, Bb, B


## results
see `DWK.csv`
and `DWK_sum.csv`

parts spelled   : 112
notes spelled   : 56953
correct spelling: 94.74 %
correct KS estim: 90.18 %

`DWK0.csv` is a former execution crashed at `get_datasum` (very last step).
the results are the same but not the execution times.

commentaires:

- fiasco tonalité BWV 848 Fugue, main gauche.
- [ ] essayer avec même global ton que m.d.
- [ ] essayer global ton m.g. = global ton m.d. comme strategie globale

- idem BWV 867 Fugue, m.g.

- idem BWV 891 Prélude, m.g.

- pour BWV 883 Prélude, c'est l'inverse: ton m.g. correct et ton m.dr. fausse
  mais moins grande diff. et faibles conséquences

- pour BWV 891 Fugue les 2 mains sont fausse (peu)

- pour BWV 887 Prelude aussi mais m.d. moins fausse que m.g.


## PSE warnings
in log file `output.log`

- [ ] examiner `[pse_debug]`
  only empty bar / enum ? -> suppr. these msg

examiner `[pse_warning]`
- [ ] `re-estimation of local tonality`
- [ ] `tie break fail` estimate global
- [ ] `tie break fail` estimation locals
- [ ] `tie break fail` > 1 best

