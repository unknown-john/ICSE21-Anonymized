# Test report for javascript / file:///tmp/top-repos-quality-repos-g_8x5w7c/booking-server.git HEAD 79f5916a3295e18ce614e96eb890a456673b2b77

### Classification report

PPCR: 0.725

| Class | Precision | Recall | Full Recall | F1-score | Full F1-score | Support | Full Support | PPCR |
|------:|:----------|:-------|:------------|:---------|:---------|:--------|:-------------|:-----|
| `∅` | 0.965| 0.995| 0.853| 0.980| 0.905| 221| 258| 0.857 |
| `"` | 1.000| 0.688| 0.393| 0.815| 0.564| 16| 28| 0.571 |
| `⏎␣⁻␣⁻␣⁻␣⁻` | 1.000| 0.938| 0.938| 0.968| 0.968| 16| 16| 1.000 |
| `⏎␣⁺␣⁺␣⁺␣⁺` | 1.000| 1.000| 0.882| 1.000| 0.938| 15| 17| 0.882 |
| `⏎` | 0.818| 0.900| 0.562| 0.857| 0.667| 10| 16| 0.625 |
| `␣` | 0.857| 0.750| 0.136| 0.800| 0.235| 8| 44| 0.182 |
| `⏎⏎` | 0.000| 0.000| 0.000| 0.000| 0.000| 1| 9| 0.111 |
| `'` | 0.000| 0.000| 0.000| 0.000| 0.000| 0| 8| 0.000 |
| `macro avg` | 0.705| 0.659| 0.471| 0.677| 0.535| 287| 396| 0.725 |
| `micro avg` | 0.962| 0.962| 0.697| 0.962| 0.808| 287| 396| 0.725 |
| `weighted avg` | 0.959| 0.962| 0.697| 0.958| 0.762| 287| 396| 0.725 |

### Confusion matrix

|refusal|  ∅| ␣| "| ⏎| ⏎␣⁺␣⁺␣⁺␣⁺| ⏎␣⁻␣⁻␣⁻␣⁻| '| ⏎⏎| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|0 |0 |0 |0 |0 |0 |0 |0 |0 |
|37 |220 |1 |0 |0 |0 |0 |0 |0 |
|36 |2 |6 |0 |0 |0 |0 |0 |0 |
|12 |5 |0 |11 |0 |0 |0 |0 |0 |
|6 |1 |0 |0 |9 |0 |0 |0 |0 |
|2 |0 |0 |0 |0 |15 |0 |0 |0 |
|0 |0 |0 |0 |1 |0 |15 |0 |0 |
|8 |0 |0 |0 |0 |0 |0 |0 |0 |
|8 |0 |0 |0 |1 |0 |0 |0 |0 |

### Files with most errors

| filename | number of errors|
|:----:|:-----|

<details>
    <summary>Machine-readable report</summary>
```json
{
  "cl_report": {"\"": {"f1-score": 0.8148148148148148, "precision": 1.0, "recall": 0.6875, "support": 16}, "\u0027": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 0}, "macro avg": {"f1-score": 0.6774568830014623, "precision": 0.7050296195033037, "recall": 0.6588093891402715, "support": 287}, "micro avg": {"f1-score": 0.9616724738675958, "precision": 0.9616724738675958, "recall": 0.9616724738675958, "support": 287}, "weighted avg": {"f1-score": 0.9584058971366274, "precision": 0.9591797040907624, "recall": 0.9616724738675958, "support": 287}, "\u2205": {"f1-score": 0.9799554565701559, "precision": 0.9649122807017544, "recall": 0.995475113122172, "support": 221}, "\u23ce": {"f1-score": 0.8571428571428572, "precision": 0.8181818181818182, "recall": 0.9, "support": 10}, "\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 1}, "\u23ce\u2423\u207a\u2423\u207a\u2423\u207a\u2423\u207a": {"f1-score": 1.0, "precision": 1.0, "recall": 1.0, "support": 15}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.967741935483871, "precision": 1.0, "recall": 0.9375, "support": 16}, "\u2423": {"f1-score": 0.7999999999999999, "precision": 0.8571428571428571, "recall": 0.75, "support": 8}},
  "cl_report_full": {"\"": {"f1-score": 0.5641025641025641, "precision": 1.0, "recall": 0.39285714285714285, "support": 28}, "\u0027": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 8}, "macro avg": {"f1-score": 0.5345818847673555, "precision": 0.7050296195033037, "recall": 0.47053586233647793, "support": 396}, "micro avg": {"f1-score": 0.8081991215226941, "precision": 0.9616724738675958, "recall": 0.696969696969697, "support": 396}, "weighted avg": {"f1-score": 0.7621618624225537, "precision": 0.9109913212784025, "recall": 0.696969696969697, "support": 396}, "\u2205": {"f1-score": 0.9053497942386831, "precision": 0.9649122807017544, "recall": 0.8527131782945736, "support": 258}, "\u23ce": {"f1-score": 0.6666666666666666, "precision": 0.8181818181818182, "recall": 0.5625, "support": 16}, "\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 9}, "\u23ce\u2423\u207a\u2423\u207a\u2423\u207a\u2423\u207a": {"f1-score": 0.9375, "precision": 1.0, "recall": 0.8823529411764706, "support": 17}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.967741935483871, "precision": 1.0, "recall": 0.9375, "support": 16}, "\u2423": {"f1-score": 0.2352941176470588, "precision": 0.8571428571428571, "recall": 0.13636363636363635, "support": 44}},
  "ppcr": 0.7247474747474747
}
```
</details>
