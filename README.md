# NLP-Parsing

NLP-Parsing is a research-focused project for exploring syntactic parsing and cross-lingual linguistic patterns, with a focus on English and Hindi Universal Dependencies (UD) datasets.

## Project Goals

- Analyze syntactic structures from UD treebanks.
- Compare language-level parsing characteristics.
- Visualize parsing trends and structural fingerprints.

## Repository Structure

```
NLP-Parsing/
├── parsing.ipynb
├── README.md
├── Dataset/
│   ├── english/
│   └── hindi/
├── arc_fingerprint.png
├── syntactic_fingerprint_heatmap.png
├── hotspot_heatmap.png
├── oracle_analysis.png
├── pas_analysis.png
└── ted_vs_length.png
```

## Dataset

The project uses Universal Dependencies `.conllu` files organized by language under:

- `Dataset/english/`
- `Dataset/hindi/`

Make sure these folders contain the expected train/dev/test splits before running analysis.

## Requirements

Recommended environment:

- Python 3.9+
- Jupyter Notebook or JupyterLab

Install common dependencies:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

If `parsing.ipynb` imports additional libraries, install them as needed.

## How To Run

1. Open the project folder.
2. Launch Jupyter:

```bash
jupyter notebook
```

3. Open `parsing.ipynb`.
4. Run cells in order to reproduce the analysis and generated visuals.

## Output Visualizations

The repository includes analysis outputs such as:

- Arc/syntactic fingerprints
- Hotspot heatmaps
- Oracle and PAS analysis plots
- TED vs. sentence length comparisons

## Notes

- Keep dataset paths unchanged unless you also update notebook paths.
- For reproducibility, run all notebook cells from a clean kernel.

## License

No license file is currently included. Add a license if you plan to distribute this project publicly.
