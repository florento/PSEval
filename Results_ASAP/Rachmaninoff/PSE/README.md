
## PSE


Rachmaninoff
Preludes

Evaluation failed to produce a table and annotated scores

Evaluation trace


```
(base) macbook-pro-3:scripts augustinbouquillard$ python evalASAP.py
What?
eval ASAP/Rachmaninoff with algo Algo.Algo_PSE
4 23 : ../../../Datasets/ASAP/Rachmaninoff/Preludes_op_23/4/xml_score.musicxml
10 Preludes Sergei Vasilievich Rachmaninoff part 1 / 2 730 notes, 77 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Bminor (2#)
[pse_debug] 1 candidates in second global list: Bminor (2#)
spell finished
global ton: OK: ( b minor ), has the same signature as <music21.key.KeySignature of 2 sharps> BEFORE diff
diff: 19
rewrite passing notes
diff: 19
10 Preludes Sergei Vasilievich Rachmaninoff part 2 / 2 647 notes, 77 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Bminor (2#)
[pse_warning] estimateLocal: ties bar 51
[pse_debug] 1 candidates in second global list: Bminor (2#)
spell finished
global ton: OK: ( b minor ), has the same signature as <music21.key.KeySignature of 2 sharps> BEFORE diff
diff: 16
rewrite passing notes
diff: 16
6 23 : ../../../Datasets/ASAP/Rachmaninoff/Preludes_op_23/6/xml_score.musicxml
10 Preludes Sergei Vasilievich Rachmaninoff part 1 / 2 679 notes, 43 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Cminor (3b)
[pse_debug] 1 candidates in second global list: Cminor (3b)
spell finished
global ton: OK: ( c minor ), has the same signature as <music21.key.KeySignature of 3 flats> BEFORE diff
diff: 11
rewrite passing notes
diff: 11
10 Preludes Sergei Vasilievich Rachmaninoff part 2 / 2 646 notes, 43 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Cminor (3b)
[pse_debug] 1 candidates in second global list: Cminor (3b)
spell finished
global ton: OK: ( c minor ), has the same signature as <music21.key.KeySignature of 3 flats> BEFORE diff
diff: 18
rewrite passing notes
diff: 18
5 32 : ../../../Datasets/ASAP/Rachmaninoff/Preludes_op_32/5/xml_score.musicxml
Prelude in G Major Sergei Rachmaninoff part 1 / 2 519 notes, 41 bars, algo PSE
add_tons 30
spell
[pse_debug] 2 candidates in first global list: Gmajor (1#) Eminor (1#)
[pse_debug] 1 candidates in second global list: Gmajor (1#)
spell finished
real global tone : <music21.key.KeySignature of 1 sharp>
possible tone :  G major
good index :  0
possible tone :  e minor
good index :  1
global ton: OK: ( G major ), has the same signature as <music21.key.KeySignature of 1 sharp> BEFORE diff
diff: 15
rewrite passing notes
diff: 15
Prelude in G Major Sergei Rachmaninoff part 2 / 2 815 notes, 41 bars, algo PSE
add_tons 30
spell
[pse_debug] 2 candidates in first global list: Gmajor (1#) Eminor (1#)
[pse_debug] 1 candidates in second global list: Gmajor (1#)
spell finished
real global tone : <music21.key.KeySignature of 1 sharp>
possible tone :  G major
good index :  0
possible tone :  e minor
good index :  1
global ton: OK: ( G major ), has the same signature as <music21.key.KeySignature of 1 sharp> BEFORE diff
diff: 0
rewrite passing notes
diff: 0
10 32 : ../../../Datasets/ASAP/Rachmaninoff/Preludes_op_32/10/xml_score.musicxml
X Серге́й Рахма́нинов part 1 / 2 1564 notes, 62 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Bminor (2#)
[pse_debug] 1 candidates in second global list: Bminor (2#)
spell finished
global ton: OK: ( b minor ), has the same signature as <music21.key.KeySignature of 2 sharps> BEFORE diff
diff: 5
rewrite passing notes
diff: 5
X Серге́й Рахма́нинов part 2 / 2 1422 notes, 62 bars, algo PSE
add_tons 30
spell
[pse_debug] 1 candidates in first global list: Bminor (2#)
[pse_debug] 1 candidates in second global list: Bminor (2#)
spell finished
global ton: OK: ( b minor ), has the same signature as <music21.key.KeySignature of 2 sharps> BEFORE diff
diff: 3
rewrite passing notes
diff: 3

PS : 98.76%
KS : 100%
```
