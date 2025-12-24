# Efficient Transformer Compression in Pre-trained Language Models Through Selective Tensor Rank Reduction

IEEE conference paper on tensor decomposition methods for compressing transformer-based language models.
IF2123 Geometric and Linear Algebra

## Abstract

This paper investigates tensor rank reduction as a structured compression technique for large language models. We apply Tucker and Tensor-Train decomposition to compress transformer feed-forward networks and attention layers, achieving 30–50% parameter reduction with less than 2% accuracy loss.

## Contents

- `Geometric-and-Linear-Algebra-IEEEPaper.tex` - Main LaTeX source
- `Geometric-and-Linear-Algebra-IEEEPaper.pdf` - Compiled paper
- `main.ipynb` - Python implementation and experiments
- `media/` - Figures and images

## Compilation

```bash
pdflatex Geometric-and-Linear-Algebra-IEEEPaper.tex
```

## Experiments

The notebook demonstrates tensor decomposition on DistilBERT for sentiment analysis (SST-2 dataset).

## Author

Made Branenda Jordhy  
13524026
ethgalleryin@gmail.com 13524026@std.stei.itb.ac.id

## License

See [LICENSE](LICENSE) file.
