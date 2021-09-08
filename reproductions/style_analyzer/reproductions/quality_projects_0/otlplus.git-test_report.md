# Test report for javascript / file:///tmp/top-repos-quality-repos-9q1ttk53/otlplus.git HEAD 4c42150d13d7ef51c08baf54a71117ab40fee93e

### Classification report

PPCR: 0.909

| Class | Precision | Recall | Full Recall | F1-score | Full F1-score | Support | Full Support | PPCR |
|------:|:----------|:-------|:------------|:---------|:---------|:--------|:-------------|:-----|
| `∅` | 0.975| 0.991| 0.962| 0.983| 0.968| 7614| 7846| 0.970 |
| `␣` | 0.944| 0.961| 0.877| 0.952| 0.909| 3406| 3731| 0.913 |
| `'` | 0.971| 0.992| 0.992| 0.981| 0.981| 1096| 1096| 1.000 |
| `⏎` | 0.897| 0.847| 0.466| 0.871| 0.613| 430| 781| 0.551 |
| `⏎␣⁺␣⁺` | 0.940| 0.782| 0.642| 0.854| 0.763| 381| 464| 0.821 |
| `⏎␣⁻␣⁻` | 0.962| 0.841| 0.670| 0.897| 0.790| 333| 418| 0.797 |
| `"` | 0.000| 0.000| 0.000| 0.000| 0.000| 40| 40| 1.000 |
| `⏎⏎` | 0.000| 0.000| 0.000| 0.000| 0.000| 20| 223| 0.090 |
| `⏎␣⁻␣⁻␣⁻␣⁻` | 0.000| 0.000| 0.000| 0.000| 0.000| 19| 20| 0.950 |
| `⏎⏎⏎` | 0.000| 0.000| 0.000| 0.000| 0.000| 4| 54| 0.074 |
| `macro avg` | 0.569| 0.541| 0.461| 0.554| 0.503| 13343| 14673| 0.909 |
| `micro avg` | 0.963| 0.963| 0.876| 0.963| 0.917| 13343| 14673| 0.909 |
| `weighted avg` | 0.957| 0.963| 0.876| 0.960| 0.902| 13343| 14673| 0.909 |

### Confusion matrix

|refusal|  ∅| ␣| '| ⏎| ⏎␣⁺␣⁺| ⏎␣⁻␣⁻| ⏎⏎| ⏎⏎⏎| "| ⏎␣⁻␣⁻␣⁻␣⁻| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|232 |7548 |66 |0 |0 |0 |0 |0 |0 |0 |0 |
|325 |88 |3273 |2 |25 |18 |0 |0 |0 |0 |0 |
|0 |0 |9 |1087 |0 |0 |0 |0 |0 |0 |0 |
|351 |14 |51 |0 |364 |1 |0 |0 |0 |0 |0 |
|83 |40 |33 |10 |0 |298 |0 |0 |0 |0 |0 |
|85 |33 |16 |0 |4 |0 |280 |0 |0 |0 |0 |
|203 |7 |0 |0 |13 |0 |0 |0 |0 |0 |0 |
|50 |4 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|0 |0 |20 |20 |0 |0 |0 |0 |0 |0 |0 |
|1 |8 |0 |0 |0 |0 |11 |0 |0 |0 |0 |

### Files with most errors

| filename | number of errors|
|:----:|:-----|

<details>
    <summary>Machine-readable report</summary>
```json
{
  "cl_report": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 40}, "\u0027": {"f1-score": 0.981489841986456, "precision": 0.9714030384271671, "recall": 0.9917883211678832, "support": 1096}, "macro avg": {"f1-score": 0.5538959807395003, "precision": 0.5688930668544474, "recall": 0.5413576040654013, "support": 13343}, "micro avg": {"f1-score": 0.9630517874540958, "precision": 0.9630517874540958, "recall": 0.9630517874540958, "support": 13343}, "weighted avg": {"f1-score": 0.9595215001246196, "precision": 0.9567897009362174, "recall": 0.9630517874540958, "support": 13343}, "\u2205": {"f1-score": 0.9830685074238082, "precision": 0.974941875484371, "recall": 0.9913317572892041, "support": 7614}, "\u23ce": {"f1-score": 0.8708133971291867, "precision": 0.896551724137931, "recall": 0.8465116279069768, "support": 430}, "\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 20}, "\u23ce\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 4}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.8538681948424068, "precision": 0.9400630914826499, "recall": 0.7821522309711286, "support": 381}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.8974358974358975, "precision": 0.9621993127147767, "recall": 0.8408408408408409, "support": 333}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 19}, "\u2423": {"f1-score": 0.9522839685772476, "precision": 0.9437716262975778, "recall": 0.96095126247798, "support": 3406}},
  "cl_report_full": {"\"": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 40}, "\u0027": {"f1-score": 0.981489841986456, "precision": 0.9714030384271671, "recall": 0.9917883211678832, "support": 1096}, "macro avg": {"f1-score": 0.5025499978153766, "precision": 0.5688930668544474, "recall": 0.46092188715618143, "support": 14673}, "micro avg": {"f1-score": 0.9173329525985152, "precision": 0.9630517874540958, "recall": 0.8757581953247461, "support": 14673}, "weighted avg": {"f1-score": 0.9016482105007096, "precision": 0.938721400299684, "recall": 0.8757581953247461, "support": 14673}, "\u2205": {"f1-score": 0.968437259430331, "precision": 0.974941875484371, "recall": 0.962018863114963, "support": 7846}, "\u23ce": {"f1-score": 0.6133108677337826, "precision": 0.896551724137931, "recall": 0.4660691421254802, "support": 781}, "\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 223}, "\u23ce\u23ce\u23ce": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 54}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.763124199743918, "precision": 0.9400630914826499, "recall": 0.6422413793103449, "support": 464}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.7898448519040903, "precision": 0.9621993127147767, "recall": 0.6698564593301436, "support": 418}, "\u23ce\u2423\u207b\u2423\u207b\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 20}, "\u2423": {"f1-score": 0.9092929573551883, "precision": 0.9437716262975778, "recall": 0.8772447065129992, "support": 3731}},
  "ppcr": 0.9093573229741703
}
```
</details>