
## How to Run

1. Open BestModel/train_best_model.ipynb in Google Colab
2. Ensure GPU runtime is enabled
3. Run all cells
4. dev.txt and test.txt will be generated

Model:
- Base: roberta-base
- Epochs: 5
- Learning rate: 2e-5
- Max length: 160
- Class-weighted loss
- Best dev F1 (positive class): 0.6284
