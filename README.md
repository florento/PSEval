# PSeval
evaluation results of engraving-based pitch-spelling algos (PSE and PS13b), 
on different datasets.

- the last results on the ASAP copora are in directory `Results_ASAP`
- the last results on the Lamarque-Goudard (LG) copora are in directory `Results_ASAP`
- the directory `archives` contains older evaluations (obsolete)

The evaluation directories contain 
- evaluation table in `cvs` format (1 row / score file evaluated)
- evaluation summary in `cvs` format
- score files (MusicXML) annotated with color codes:
  - red note in case of an error
  - green note in case of an initial spelling error then corrected by the rewriting) 
  - estimated local keys in each measure

