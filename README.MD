# Text Classification
The purpose of this repo was to test out basic layers such as lstm and text vectorization layers

# TODO
- [x] text vectorization layer
- [x] lstm model
- [x] Write a simple tensorflow dense layer using simple classifier
- [x] Wrote for multi class problem, added return sequence for lstm
- [x] Try bert with tensorflow official models
- [x] Use tf hub with universal sentence embeddings
- [ ] Check overfit reason

# Model Results
| Model Name                    | Accuracy | MCC  |
|-------------------------------|----------|------|
| Basic LSTM                    | 0.86     | 0.72 |
| BERT                          | 0.89     | 0.78 |
| Universal Sentence Embeddings | 0.96     | 0.91 |