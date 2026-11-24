# Dataset

The dataset is not stored in this repository because of its size (about 40 MB as a zip). It contains **566 images** collected from online sources, organised by fruit and freshness.

## Expected folder layout

The notebook expects a zip file named `Fruit_dataset.zip` with this structure:

```
Fruit_dataset/
├── Apple/
│   ├── Fresh/
│   └── Rotten/
├── Banana/
│   ├── Fresh/
│   └── Rotten/
└── Strawberry/
    ├── Fresh/
    └── Rotten/
```

## Raw image counts

| Class | Images |
|---|---|
| Apple – Fresh | 124 |
| Apple – Rotten | 55 |
| Banana – Fresh | 33 |
| Banana – Rotten | 90 |
| Strawberry – Fresh | 220 |
| Strawberry – Rotten | 44 |
| **Total** | **566** |

The classes are unequal, so the notebook trims every class to the size of the smallest one (33 images) before training. See the main README for details.
