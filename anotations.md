# Anotation in XML files
evaluations of pitch-spelling algos  
display of results (diff) in score (xml) files.

## color codes
The note in XML scores are colored

For a Pitch-Spelling algo in two steps:
1. first spelling
2. [optional] rewriting (for passing notes *etc*)


For every note, (ref. is the reference score):

|                 | step 1 | step 2 | color
|-----------------|--------|--------|--------|
| status wrt ref. |  $=$   |  $=$   | black  |
| status wrt ref. |  $=$   | $\neq$ | violet |
| status wrt ref. | $\neq$ |  $=$   | green  |
| status wrt ref. | $\neq$ | $\neq$ | red    | si step1 = step2
| status wrt ref. | $\neq$ | $\neq$ | orange | si step1 $\neq$ step2



## global ton
- KS original (ref)
- ref global ton, estimated global ton, nb candidates (PSE)
  name and (int) KS
  in `TextExpression` expression, bold
  above first staff, first bar.

## local tons
#### PSE and PS14
- estimated local ton
  name and KS (int)
  in `TextExpression` expression, italic
  below bar when change

#### PS13
- estimated local ton
  name and KS (int)
  in `TextExpression` expression, italic
  below note when change

