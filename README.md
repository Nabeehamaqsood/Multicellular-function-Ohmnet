# Multicellular Function Prediction with Multi-layer Tissue Networks (FYP)

Final Year Project: predicting protein function across tissues using tissue-specific
protein-protein interaction networks, based on **OhmNet** (Zitnik & Leskovec, 2017).
The project re-implements OhmNet (hierarchy-aware node embeddings), optimizes it,
and extends it with a GNN-based model.

## Notebooks
| Notebook | Description |
|---|---|
| `FYP_Ohmnet (1).ipynb` | OhmNet implementation (utility, model, main) on Google Colab |
| `Ohmnet_customized.ipynb` | Customized OhmNet with evaluation and plots |
| `Ohmnet_customized_V2.ipynb` | Optimized OhmNet (parallel walks, GPU, GraphSAGE) |
| `GNN.ipynb` | Enhanced GNN-OhmNet model |

## Dataset
Tissue networks, labels and hierarchy from SNAP:
http://snap.stanford.edu/ohmnet/ — download `bio-tissue-networks`,
`bio-tissue-labels`, `bio-tissue-hierarchy` and extract them next to the notebooks.

## Setup
```bash
pip install networkx numpy gensim scikit-learn matplotlib seaborn torch torch-geometric
```
The notebooks were run on Google Colab; update the Google Drive paths inside them
if you run elsewhere.

## Reference
Zitnik M., Leskovec J. *Predicting multicellular function through multi-layer tissue networks.* Bioinformatics, 2017.

## Author
Nizam ul Din Qureshi — [GitHub](https://github.com/NizELITe)
