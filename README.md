# Privatizing Recommendation Datasets with
Differential Privacy

# Results

| Original |            |         | eps_exp = 4 |            |                   |            |            |                   |            |            |                   |
|:--------:|:----------:|:-------:|:-----------:|:----------:|:-----------------:|:----------:|:----------:|:-----------------:|:----------:|:----------:|:-----------------:|
| No Noise |            |         |  eps_rr = 6 |            |                   | eps_rr = 4 |            |                   | eps_rr = 6 |            |                   |
| Model    | nDCG       | Ranking | Model       | nDCG       | Ranking Variation | Model      | nDCG       | Ranking Variation | Model      | nDCG       | Ranking Variation |
| RP3beta  | 0,12582858 | 1       | EASER       | 0,10648203 | 1                 | EASER      | 0,0494139  | 1                 | MostPop    | 0,08268632 | 3                 |
| EASER    | 0,11939761 | 2       | ItemKNN     | 0,08468585 | 1                 | MostPop    | 0,04778822 | 2                 | EASER      | 0,08102164 | 0                 |
| ItemKNN  | 0,09214594 | 3       | MostPop     | 0,0841105  | 1                 | RP3beta    | 0,04751652 | -2                | RP3beta    | 0,07931767 | -2                |
| MostPop  | 0,09033883 | 4       | RP3beta     | 0,07899349 | -3                | ItemKNN    | 0,02413369 | -1                | ItemKNN    | 0,07507059 | -1                |
| Random   | 0,00765841 | 5       | Random      | 0,00787496 | 0                 | Random     | 0,01199508 | 0                 | Random     | 0,07150299 | 0                 |
