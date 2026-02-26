# PyTorch Backprop in Action 

This portfolio piece demonstrates an end-to-end, **reproducible** PyTorch workflow:

- Build a simple neural network (MLP) for a toy classification task (2D *moons* / *circles*)
- Train it with a clean training loop and show **backpropagation** using `loss.backward()`
- Experiment with architectures (depth/width) and activations (ReLU/Tanh/LeakyReLU)
- Visualize results (loss/accuracy curves, decision boundaries)
- Discuss limitations and tradeoffs

## Project Structure

```
your-portfolio-piece/
├── README.md
├── notebooks/
│   └── main_analysis.ipynb
└── outputs/
    ├── figures/
    └── checkpoints/
```

## Setup (VS Code)

1) Create a virtual environment 

```bash
python -m venv .venv
source .venv/bin/activate  
```

2) Install dependencies

```bash
pip install -r requirements.txt
```

3) Open VS Code → select the `.venv` interpreter.

## Run

Open and run the notebook:

- `notebooks/main_analysis.ipynb`

Outputs:
- Figures saved in `outputs/figures/`
- Best model checkpoints saved in `outputs/checkpoints/`

## Rubric Mapping 

### Conceptual Understanding
- Notebook explains *why* MLP + CrossEntropyLoss + Adam are chosen for this task.
- Connects to course material: gradients/backprop, activations, capacity vs generalization.

### Technical Implementation
- Code runs end-to-end and saves artifacts (plots + checkpoint).
- Clean separation of dataset/model/training/eval.

### Code Quality & Documentation
- Notebook is a guided story.

### Critical Analysis
- Compares architectures/activations.
- Discusses limitations: toy data, non-robustness, hyperparameter sensitivity.




