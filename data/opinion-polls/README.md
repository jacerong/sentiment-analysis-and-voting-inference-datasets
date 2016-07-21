### Description
Opinion polls were filtered by their survey period in order that they corresponded with the collection period of Twitter data (i.e., the COpres14 set). Thus, polls conducted between May 03, 2014 and May 15, 2014 were collected to infer voting in the first round election; likewise, those whose survey period was in the range from May 26, 2014 to June 04, 2014 were collected to infer voting in the run-off election.

### Files
1. **dataset.tsv** (tab-separated values): the i-th row in the file corresponds to the i-th poll collected.

### Features
1. pollster.
2. since (YYYY-MM-DD): starting date of the survey period.
3. up to (YYYY-MM-DD): ending date of the survey period.
4. sample size (of the survey).
5. santos (Juan Manuel Santos): _see notes below_.
6. zuluaga (Óscar Iván Zuluaga): _see notes below_.
7. ramirez (Marta Lucía Ramírez): _see notes below_.
8. lopez (Clara López): _see notes below_.
9. penalosa (Enrique Peñalosa): _see notes below_.
10. blank (vote): _see notes below_.
11. undecised (voters): _see notes below_.
12. source.

#### Notes.
1. The value corresponds to the voting share the candidate/electoral option would receive according to the poll.
2. All values are given in percentages.
3. The decimal separator character used is the dot (.).
4. The "-1.00" value (with no quotes) is used as wildcard, which means discarding the column value.
