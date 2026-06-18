# Data folder

Place the manuscript-supporting metadata file and image folder here.

Expected example structure:

```text
data/
├── zymo_labelled_data.xlsx
└── phibase_assay_images/
    ├── image_1.png
    ├── image_2.png
    └── ...
```

The Excel file is expected to contain two sheets:

- `Figures`
- `Captions`

The `Figures` sheet should include:

- `pmid`
- `filename`
- `assay_label`
- `label`

The `Captions` sheet should include:

- `pmid`
- `caption`

Do not upload copyrighted images or restricted data unless you have permission to share them.
