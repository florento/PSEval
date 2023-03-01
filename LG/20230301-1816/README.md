# PS eval: Lamarque-Goudard dataset

complete evaluation LG dataset
01 mars 2023
version PSE: v0.7 (orderings)

PSeval 
- 26 tonalities: maj and min harm, KS in -6...6
- ordering lex(accid, non-dia, dist, color) for 
	- init PSB, 
	- PSV (locals), 
	- PST global 
- ordering lex(approx(accid), non-dia, dist, color) for
	- PST globals (candidates)
  approx. coeff 3%

dist. ton = Weber

## table

`LGeval26_20230301-1816.csv`

parts spelled   : 249
notes spelled   : 27687
correct spelling: 97.35 %
correct KS estim: 73.49 %

tres légère amélioration par rapport au cas sans approx.



## TODO

in log file `LGeval26_20230301-1816.log`

grosses catastrophe est. ton. global:
examiner la table et les totaux pour estim. globals
- [x] 228 (+6 vs -5)
- [x] 405 (-6 vs 6)
- [x] 445 (5 vs -6)

autres cata:
- [ ] 302 (-2 vs 0)  Ibert
- [ ] 332 (4 vs 0) Milhaud


