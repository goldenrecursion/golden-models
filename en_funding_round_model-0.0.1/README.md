| Feature | Description |
| --- | --- |
| **Name** | `en_funding_round_model` |
| **Version** | `0.0.1` |
| **spaCy** | `>=3.1.0,<3.2.0` |
| **Default Pipeline** | `tok2vec`, `ner` |
| **Components** | `tok2vec`, `ner` |
| **Vectors** | 0 keys, 0 unique vectors (0 dimensions) |
| **Sources** | n/a |
| **License** | n/a |
| **Author** | [n/a]() |

### Label Scheme

<details>

<summary>View label scheme (5 labels for 1 components)</summary>

| Component | Labels |
| --- | --- |
| **`ner`** | `DATE`, `FUNDED_COMPANY`, `INVESTOR`, `MONEY`, `ROUND` |

</details>

### Accuracy

| Type | Score |
| --- | --- |
| `ENTS_F` | 99.55 |
| `ENTS_P` | 99.50 |
| `ENTS_R` | 99.60 |
| `TOK2VEC_LOSS` | 102154.27 |
| `NER_LOSS` | 54447.03 |