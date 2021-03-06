# Test report for javascript / file:///tmp/top-repos-quality-repos-t6zjqnfc/redux HEAD 902484ed735d38aec06683c847810a7218d8dba2

### Classification report

PPCR: 0.908

| Class | Precision | Recall | Full Recall | F1-score | Full F1-score | Support | Full Support | PPCR |
|------:|:----------|:-------|:------------|:---------|:---------|:--------|:-------------|:-----|
| `∅` | 0.930| 0.979| 0.929| 0.954| 0.930| 2379| 2508| 0.949 |
| `␣` | 0.914| 0.929| 0.827| 0.921| 0.868| 1400| 1571| 0.891 |
| `'` | 0.974| 0.932| 0.932| 0.953| 0.953| 444| 444| 1.000 |
| `⏎␣⁺␣⁺` | 0.862| 0.699| 0.593| 0.772| 0.702| 206| 243| 0.848 |
| `⏎␣⁻␣⁻` | 0.928| 0.819| 0.732| 0.870| 0.819| 204| 228| 0.895 |
| `⏎` | 0.891| 0.751| 0.496| 0.815| 0.638| 185| 280| 0.661 |
| `⏎⏎` | 0.912| 0.823| 0.578| 0.865| 0.707| 113| 161| 0.702 |
| `"` | 0.000| 0.000| 0.000| 0.000| 0.000| 20| 20| 1.000 |
| `⏎␣⁻␣⁻␣⁻␣⁻` | 0.000| 0.000| 0.000| 0.000| 0.000| 5| 6| 0.833 |
| `weighted avg` | 0.920| 0.925| 0.840| 0.922| 0.873| 4956| 5461| 0.908 |
| `macro avg` | 0.712| 0.659| 0.565| 0.683| 0.624| 4956| 5461| 0.908 |
| `micro avg` | 0.925| 0.925| 0.840| 0.925| 0.880| 4956| 5461| 0.908 |

### Confusion matrix

|refusal|  ∅| ␣| '| ⏎| ⏎␣⁺␣⁺| ⏎␣⁻␣⁻| ⏎⏎| "| ⏎␣⁻␣⁻␣⁻␣⁻| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|129 |2329 |47 |0 |0 |1 |2 |0 |0 |0 |
|171 |59 |1300 |0 |8 |22 |8 |3 |0 |0 |
|0 |26 |2 |414 |2 |0 |0 |0 |0 |0 |
|95 |2 |38 |0 |139 |0 |0 |6 |0 |0 |
|37 |46 |15 |1 |0 |144 |0 |0 |0 |0 |
|24 |36 |1 |0 |0 |0 |167 |0 |0 |0 |
|48 |0 |13 |0 |7 |0 |0 |93 |0 |0 |
|0 |3 |7 |10 |0 |0 |0 |0 |0 |0 |
|1 |2 |0 |0 |0 |0 |3 |0 |0 |0 |

### Files with most errors

| filename | number of errors|
|:----:|:-----|

<details>
    <summary>Machine-readable report</summary>
```json
{
  "cl_report": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 20}, "\u0027": {"f1-score": 0.952819332566168, "precision": 0.9741176470588235, "recall": 0.9324324324324325, "support": 444}, "macro avg": {"f1-score": 0.6833575216322204, "precision": 0.7123341706704616, "recall": 0.6591114894416368, "support": 4956}, "micro avg": {"f1-score": 0.9253430185633575, "precision": 0.9253430185633575, "recall": 0.9253430185633575, "support": 4956}, "weighted avg": {"f1-score": 0.9215855537415905, "precision": 0.9200728226738047, "recall": 0.9253430185633575, "support": 4956}, "\u2205": {"f1-score": 0.954117165096272, "precision": 0.9304834198961246, "recall": 0.9789827658680118, "support": 2379}, "\u23ce": {"f1-score": 0.81524926686217, "precision": 0.8910256410256411, "recall": 0.7513513513513513, "support": 185}, "\u23ce\u23ce": {"f1-score": 0.8651162790697673, "precision": 0.9117647058823529, "recall": 0.8230088495575221, "support": 113}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.7721179624664879, "precision": 0.8622754491017964, "recall": 0.6990291262135923, "support": 206}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.8697916666666667, "precision": 0.9277777777777778, "recall": 0.8186274509803921, "support": 204}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 5}, "\u2423": {"f1-score": 0.9210060219624513, "precision": 0.9135628952916374, "recall": 0.9285714285714286, "support": 1400}},
  "cl_report_full": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 20}, "\u0027": {"f1-score": 0.952819332566168, "precision": 0.9741176470588235, "recall": 0.9324324324324325, "support": 444}, "macro avg": {"f1-score": 0.6240759193440711, "precision": 0.7123341706704616, "recall": 0.5652973651298755, "support": 5461}, "micro avg": {"f1-score": 0.8804838245176155, "precision": 0.9253430185633575, "recall": 0.8397729353598242, "support": 5461}, "weighted avg": {"f1-score": 0.8731683753648134, "precision": 0.9190103507592141, "recall": 0.8397729353598242, "support": 5461}, "\u2205": {"f1-score": 0.9295549790460986, "precision": 0.9304834198961246, "recall": 0.9286283891547049, "support": 2508}, "\u23ce": {"f1-score": 0.6376146788990826, "precision": 0.8910256410256411, "recall": 0.49642857142857144, "support": 280}, "\u23ce\u23ce": {"f1-score": 0.7072243346007604, "precision": 0.9117647058823529, "recall": 0.577639751552795, "support": 161}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.7024390243902437, "precision": 0.8622754491017964, "recall": 0.5925925925925926, "support": 243}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.8186274509803921, "precision": 0.9277777777777778, "recall": 0.7324561403508771, "support": 228}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 6}, "\u2423": {"f1-score": 0.8684034736138944, "precision": 0.9135628952916374, "recall": 0.8274984086569064, "support": 1571}},
  "ppcr": 0.9075260941219557
}
```
</details>
