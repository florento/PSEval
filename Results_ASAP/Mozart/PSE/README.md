## PSE

Mozart 
- Sonata 8-1 
- Sonata 12-1 12-2 12-3
- Fantasie 475

Music 21 failed to produced the annotated scores


Evaluation trace
20230707-1545


```
(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 1667 notes, 133 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Aminor (0)
[pse_warning] estimateLocal: ties bar 27
[pse_warning] estimateLocal: ties bar 123
[pse_debug] 1 candidates in second global list: Aminor (0)
global ton: OK: ( a minor ), has the same signature as <music21.key.KeySignature of no sharps or flats> diff: 10
diff: 10
None None part 2 / 2 1599 notes, 133 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Aminor (0)
[pse_warning] estimateLocal: ties bar 71
[pse_warning] estimateLocal: ties bar 93
[pse_debug] 1 candidates in second global list: Aminor (0)
global ton: OK: ( a minor ), has the same signature as <music21.key.KeySignature of no sharps or flats> diff: 26
diff: 26
(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 3 key changes cannot spell, skip
None None part 2 / 2 3 key changes cannot spell, skip
(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 1426 notes, 229 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Dminor (1b)
[pse_warning] estimateLocal: ties bar 51
[pse_warning] estimateLocal: ties bar 193
[pse_debug] 1 candidates in second global list: Dminor (1b)
global ton: OK: ( d minor ), has the same signature as F major diff: 10
diff: 10
None None part 2 / 2 1052 notes, 229 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Dminor (1b)
[pse_warning] estimateLocal: ties bar 45
[pse_warning] estimateLocal: ties bar 47
[pse_warning] estimateLocal: ties bar 116
[pse_warning] estimateLocal: ties bar 127
[pse_debug] 1 candidates in second global list: Dminor (1b)
global ton: OK: ( d minor ), has the same signature as F major diff: 6
diff: 6
(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 646 notes, 40 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Gminor (2b)
[pse_debug] 1 candidates in second global list: Gminor (2b)
global ton: OK: ( g minor ), has the same signature as B- major diff: 2
diff: 2
None None part 2 / 2 665 notes, 40 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Gminor (2b)
[pse_debug] 1 candidates in second global list: Gminor (2b)
global ton: OK: ( g minor ), has the same signature as B- major diff: 5
diff: 5
Traceback (most recent call last):
  File "/Users/augustinbouquillard/Desktop/INRIA/PitchSpelling/pse/scripts/evalASAP.py", line 181, in <module>
    eval_Mozart()
  File "/Users/augustinbouquillard/Desktop/INRIA/PitchSpelling/pse/scripts/evalASAP.py", line 176, in eval_Mozart
    eval_asapscore(sid=no, file=filep, stat=stat,
  File "/Users/augustinbouquillard/Desktop/INRIA/PitchSpelling/pse/scripts/evalASAP.py", line 111, in eval_asapscore
    write_score(s, title, composer)
  File "/Users/augustinbouquillard/Desktop/INRIA/PitchSpelling/pse/scripts/evalASAP.py", line 96, in write_score
    score.write('musicxml', fp=output_dir(composer)/(title+'.musicxml'))
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/stream/base.py", line 391, in write
    return super().write(fmt=fmt, fp=fp, **keywords)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/base.py", line 2815, in write
    return formatWriter.write(self,
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/converter/subConverters.py", line 1123, in write
    dataBytes = generalExporter.parse()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 432, in parse
    return self.parseWellformedObject(outObj)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 448, in parseWellformedObject
    scoreExporter.parse()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 1519, in parse
    self.parsePartlikeScore()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 1705, in parsePartlikeScore
    part_ex.parse()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 2742, in parse
    raise e
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 2736, in parse
    mxMeasure = measureExporter.parse()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 3174, in parse
    self.mainElementsParse()
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 3202, in mainElementsParse
    self.parseFlatElements(v, backupAfterwards=backupAfterwards)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 3266, in parseFlatElements
    self.parseOneElement(n)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 3313, in parseOneElement
    meth(o)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 3886, in noteToXml
    mxType.text = typeToMusicXMLType(d.type)
  File "/Users/augustinbouquillard/anaconda3/lib/python3.10/site-packages/music21/musicxml/m21ToXml.py", line 102, in typeToMusicXMLType
    raise MusicXMLExportException('Cannot convert inexpressible durations to MusicXML.')
music21.musicxml.xmlObjects.MusicXMLExportException: In part (Midi_1), measure (27): Cannot convert inexpressible durations to MusicXML.
(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 1809 notes, 245 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Dminor (1b)
[pse_warning] estimateLocal: ties bar 102
[pse_warning] estimateLocal: ties bar 138
[pse_debug] 1 candidates in second global list: Dminor (1b)
global ton: OK: ( d minor ), has the same signature as F major diff: 31
diff: 31
None None part 2 / 2 1179 notes, 245 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Dminor (1b)
[pse_warning] estimateLocal: ties bar 40
[pse_warning] estimateLocal: ties bar 61
[pse_warning] estimateLocal: ties bar 72
[pse_warning] estimateLocal: ties bar 118
[pse_warning] estimateLocal: ties bar 120
[pse_warning] estimateLocal: ties bar 158
[pse_warning] estimateLocal: ties bar 160
[pse_warning] estimateLocal: ties bar 168
[pse_warning] estimateLocal: ties bar 184
[pse_warning] estimateLocal: ties bar 229
[pse_debug] 1 candidates in second global list: Dminor (1b)
global ton: OK: ( d minor ), has the same signature as F major diff: 13
diff: 13

(base) MacBook-Pro-2:scripts augustinbouquillard$ python evalASAP.py
What?
None None part 1 / 2 2383 notes, 180 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Gminor (2b)
[pse_warning] estimateLocal: ties bar 46
[pse_warning] estimateLocal: ties bar 54
[pse_warning] estimateLocal: ties bar 76
[pse_warning] estimateLocal: ties bar 111
[pse_debug] 1 candidates in second global list: Gminor (2b)
global ton: NO: ( g minor was C major ), diff: 188
diff: 188
None None part 2 / 2 1404 notes, 180 bars, add_tons 30
[pse_debug] 1 candidates in first global list: Gminor (2b)
[pse_warning] estimateLocal: ties bar 3
[pse_warning] estimateLocal: ties bar 32
[pse_warning] estimateLocal: ties bar 134
[pse_warning] estimateLocal: ties bar 171
[pse_debug] 1 candidates in second global list: Gminor (2b)
global ton: NO: ( g minor was C major ), diff: 50
diff: 50
```
