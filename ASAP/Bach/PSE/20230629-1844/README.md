# PS eval: ASAP dataset, Bach
evaluation of Wohltemperierte Clavier, Preludes & Fugues
29 juin 2023

PSE with 30 tonalities
correction tonalités enharmoniques

version PSE: cb7589b72f159f84f89f63896e28c47cd9241ed9 branch PS14
BEFORE debug costADlex 
`CostADlex::update` calls `CostAD::update99`

ordre costADlex, 4 composantes:
- nb accid
- distance / local ton (cumul avec 1er)
- color
- Cb/B#, Fb/E#

excluded:
- BWV 856, Prelude
- BWV 873, Prelude

parts spelled   : 110
notes spelled   : 55530
correct spelling: 98.86 %
correct KS estim: 99.09 %