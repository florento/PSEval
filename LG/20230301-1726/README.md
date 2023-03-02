# PS eval: Lamarque-Goudard dataset

complete evaluation LG dataset
01 mars 2023
version PSE: v0.7 (orderings)

PSeval 
- with 26 tonalities: maj and min harm, KS in -6...6
- with ordering lex(accid + non-dia, dist, color) for 
	- init PSB, 
	- PSV (locals), 
	- PST global 
	- PST globals (candidates)

dist. ton = Weber

## table

`LGeval26_20230301-1726.csv`

parts spelled   : 249
notes spelled   : 27687
correct spelling: 96.61 %
correct KS estim: 72.69 %

## TODO

in log file `20230227-1405.log`

- [ ] why `265 entries` and `parts spelled : 249` ?

- [ ] examiner `[pse_debug]`

examiner `[pse_warning]`

- [ ] `re-estimation of local tonality`
- [ ] `tie break fail` estimate global
- [ ] `tie break fail` estimation locals
- [ ] `tie break fail` > 1 best
