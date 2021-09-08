# Train report for javascript / file:///tmp/top-repos-quality-repos-asunvohv/builderbookclone.git HEAD 697b7e1211702b23156ebf17cb2f077a96593901

### Classification report

PPCR: 0.867

| Class | Precision | Recall | Full Recall | F1-score | Full F1-score | Support | Full Support | PPCR |
|------:|:----------|:-------|:------------|:---------|:---------|:--------|:-------------|:-----|
| `∅` | 0.981| 0.996| 0.950| 0.989| 0.965| 78555| 82371| 0.954 |
| `␣` | 0.984| 0.969| 0.759| 0.977| 0.857| 33909| 43291| 0.783 |
| `'` | 0.998| 1.000| 0.968| 0.999| 0.983| 11789| 12184| 0.968 |
| `⏎␣⁻␣⁻` | 0.945| 0.954| 0.860| 0.949| 0.900| 5282| 5860| 0.901 |
| `⏎` | 0.968| 0.747| 0.461| 0.843| 0.624| 4901| 7939| 0.617 |
| `⏎␣⁺␣⁺` | 0.965| 0.949| 0.704| 0.957| 0.814| 4363| 5886| 0.741 |
| `"` | 1.000| 0.992| 0.971| 0.996| 0.985| 2600| 2656| 0.979 |
| `⏎⏎` | 0.728| 0.968| 0.325| 0.831| 0.449| 1511| 4503| 0.336 |
| `⏎⏎␣⁻␣⁻` | 0.000| 0.000| 0.000| 0.000| 0.000| 31| 112| 0.277 |
| `⏎␣⁺␣⁺␣⁺␣⁺` | 0.000| 0.000| 0.000| 0.000| 0.000| 12| 120| 0.100 |
| `micro avg` | 0.978| 0.978| 0.848| 0.978| 0.908| 142953| 164922| 0.867 |
| `weighted avg` | 0.978| 0.978| 0.848| 0.977| 0.899| 142953| 164922| 0.867 |
| `macro avg` | 0.757| 0.758| 0.600| 0.754| 0.658| 142953| 164922| 0.867 |

### Confusion matrix

|refusal|  ∅| ␣| '| ⏎| ⏎␣⁺␣⁺| ⏎␣⁻␣⁻| ⏎⏎| "| ⏎⏎␣⁻␣⁻| ⏎␣⁺␣⁺␣⁺␣⁺| 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |0 |
|3816 |78253 |212 |0 |0 |36 |54 |0 |0 |0 |0 |
|9382 |620 |32869 |0 |96 |104 |215 |5 |0 |0 |0 |
|395 |0 |0 |11789 |0 |0 |0 |0 |0 |0 |0 |
|3038 |450 |254 |0 |3659 |0 |0 |538 |0 |0 |0 |
|1523 |191 |30 |0 |0 |4142 |0 |0 |0 |0 |0 |
|578 |235 |9 |0 |0 |0 |5038 |0 |0 |0 |0 |
|2992 |5 |19 |0 |25 |0 |0 |1462 |0 |0 |0 |
|56 |0 |0 |20 |0 |0 |0 |0 |2580 |0 |0 |
|81 |5 |0 |0 |0 |0 |24 |2 |0 |0 |0 |
|108 |0 |0 |0 |0 |12 |0 |0 |0 |0 |0 |

### Files with most errors

| filename | number of errors|
|:----:|:-----|
| server/models/Chapter.js | 42 |
| server/api/sync-all-inside-fork.js | 41 |
| server/api/sync-one-inside-fork.js | 40 |
| server/models/Book.js | 39 |
| tutorials/5-end-nobabel/.eslintrc.js | 31 |
| components/admin/GiveFreeBook.js | 30 |
| book/8-end/server/models/Chapter.js | 28 |
| book/8-start/server/models/Chapter.js | 27 |
| book/6-end/server/models/Chapter.js | 27 |
| book/7-start/server/models/Chapter.js | 27 |

<details>
    <summary>Machine-readable report</summary>
```json
{
  "cl_report": {"\"": {"f1-score": 0.9961389961389961, "precision": 1.0, "recall": 0.9923076923076923, "support": 2600}, "\u0027": {"f1-score": 0.9991524705483515, "precision": 0.9983063764925058, "recall": 1.0, "support": 11789}, "macro avg": {"f1-score": 0.754109224939816, "precision": 0.7569812649087903, "recall": 0.7575098560157405, "support": 142953}, "micro avg": {"f1-score": 0.9778878372611978, "precision": 0.9778878372611978, "recall": 0.9778878372611978, "support": 142953}, "weighted avg": {"f1-score": 0.9774189592067254, "precision": 0.9783825872632235, "recall": 0.9778878372611978, "support": 142953}, "\u2205": {"f1-score": 0.9885796581477317, "precision": 0.9811181183314736, "recall": 0.996155559798867, "support": 78555}, "\u23ce": {"f1-score": 0.8429904388895287, "precision": 0.967989417989418, "recall": 0.7465823301367068, "support": 4901}, "\u23ce\u23ce": {"f1-score": 0.8311540648095509, "precision": 0.7284504235176881, "recall": 0.9675711449371277, "support": 1511}, "\u23ce\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 31}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.956913480420469, "precision": 0.9646017699115044, "recall": 0.9493467797387118, "support": 4363}, "\u23ce\u2423\u207a\u2423\u207a\u2423\u207a\u2423\u207a": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 12}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.949401677188354, "precision": 0.9450384543237667, "recall": 0.9538053767512306, "support": 5282}, "\u2423": {"f1-score": 0.9767614632551781, "precision": 0.9843080885215464, "recall": 0.9693296764870684, "support": 33909}},
  "cl_report_full": {"\"": {"f1-score": 0.985485103132162, "precision": 1.0, "recall": 0.9713855421686747, "support": 2656}, "\u0027": {"f1-score": 0.982703288459134, "precision": 0.9983063764925058, "recall": 0.9675804333552199, "support": 12184}, "macro avg": {"f1-score": 0.6578488516568516, "precision": 0.7569812649087903, "recall": 0.5997222160570808, "support": 164922}, "micro avg": {"f1-score": 0.9081088103938287, "precision": 0.9778878372611978, "recall": 0.8476249378494076, "support": 164922}, "weighted avg": {"f1-score": 0.8989823666310962, "precision": 0.9727469863511677, "recall": 0.8476249378494076, "support": 164922}, "\u2205": {"f1-score": 0.9653117868377228, "precision": 0.9811181183314736, "recall": 0.9500066771072343, "support": 82371}, "\u23ce": {"f1-score": 0.6244560116050857, "precision": 0.967989417989418, "recall": 0.4608892807658395, "support": 7939}, "\u23ce\u23ce": {"f1-score": 0.4491551459293395, "precision": 0.7284504235176881, "recall": 0.32467244059515876, "support": 4503}, "\u23ce\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 112}, "\u23ce\u2423\u207a\u2423\u207a": {"f1-score": 0.8137524557956778, "precision": 0.9646017699115044, "recall": 0.7037037037037037, "support": 5886}, "\u23ce\u2423\u207a\u2423\u207a\u2423\u207a\u2423\u207a": {"f1-score": 0.0, "precision": 0.0, "recall": 0.0, "support": 120}, "\u23ce\u2423\u207b\u2423\u207b": {"f1-score": 0.9003663658296847, "precision": 0.9450384543237667, "recall": 0.8597269624573379, "support": 5860}, "\u2423": {"f1-score": 0.8572583589797088, "precision": 0.9843080885215464, "recall": 0.7592571204176388, "support": 43291}},
  "ppcr": 0.8667915741987121
}
```
</details>