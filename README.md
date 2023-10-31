# PSEval
Evaluation results of the engraving-based algorithms PSE and PS13b, for joint  Pitch-Spelling and global and local Key Estimation.

The code of the algorithms can be found at https://gitlab.inria.fr/pse/pse



## Evaluation Datasets

These algorithms have been evaluation on two different datasets:

- the [ASAP](https://github.com/fosfrancesco/asap-dataset) piano dataset 
  the last results on the ASAP copora are in directory `Results_ASAP/`
-  the Lamarque-Goudard (LG) dataset with monophonic (complex) extracts
  the last results on this corpora are in directory `Results_LG/`
- the directory `Archives/` contains older evaluations and is obsolete.



## Evaluation directories

Every evaluation directory contains:

- the score files (`MusicXML`) annotated with 
  - color codes for notes with spelling errors  (see below for a precise description of colors)
  - the estimated local key for each measure
  - the estimated global key at the beginning of the score

- one evaluation table in `cvs` format 
  `.csv` file with 1 row for each score file evaluated
- one evaluation summary for the directory in `cvs` format (file `X_sum.csv` )



## Color code anotations

The notes in the score files  (`MusicXML`) are coloured according to their comparison to the spelling in the ground truth score in the dataset considered.
Both Pitch-Spelling algorithms PSE and PS13b processed in 2 steps: 

1. spelling
2. rewriting of passing notes

The comparison of the spelling result with ground truth after each step determines the color code as follows:

|                              | step 1 | step 2 | color  |
| ---------------------------- | ------ | ------ | ------ |
| comparison with ground truth | $=$    | $=$    | black  |
| comparison with ground truth | $=$    | $\neq$ | violet |
| comparison with ground truth | $\neq$ | $=$    | green  |
| comparison with ground truth | $\neq$ | $\neq$ | red    |

For instance, a green note indicates a spelling that was incorrect after step 1 but has been fixed by step 2 (rewriting), and a red note  indicates a spelling incorrect after step 1 that was not fixed by step 2.

