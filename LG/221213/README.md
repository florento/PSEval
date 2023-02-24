# PS eval: Lamarque-Goudard dataset

complete evaluation LG dataset
13 decembre 2022
version PSE: v0.5 (mono, no chords)

## `LG_0.csv`

distinguish between  

```
n.pitch.accidental == m21.pitch.Accidental('natural')
```

and

```
n.pitch.accidental == None
```

For the latter the `print_flag` must be unset to be correct.
cf. 
`PSeval.py/compare_accid`

## `LG_1.csv`

not above distiction.  

```
pse.Accid.Natural equiv. to
m21.pitch.Accidental('natural')
```

and `None`

## `LG_2.csv`

nouveau critere "mvt conjoint" dans évaluation des couts.

## `LG_3.csv`

PS with 26 tonalities (no +7, -7)
solve 2 wrong tonality detection (see `enharmoniques.md`)

- 162 (+5) 
- 363 (-5)
  parts spelled   : 250
  notes spelled   : 27406
  correct spelling: 96.86%
  correct KS estim: 70.80%
