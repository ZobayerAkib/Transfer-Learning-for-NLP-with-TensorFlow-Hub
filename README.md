# Transfer Learning for NLP with TensorFlow Hub

This project demonstrates the use of various pre-trained models for transfer learning in NLP using TensorFlow Hub.

## Training Results

| Model                              | Epoch | Accuracy | Loss  | Val Accuracy | Val Loss |
|------------------------------------|-------|----------|-------|--------------|----------|
| gnews-swivel-20dim                 | 0     | 0.9331   | 0.2729| 0.9381       | 0.1989   |
| nnlm-en-dim50                      | 0     | 0.9339   | 0.3251| 0.9381       | 0.2252   |
| gnews-swivel-20dim-finetuned       | 0     | 0.9337   | 0.3145| 0.9381       | 0.2124   |
| nnlm-en-dim128                     | 0     | 0.9213   | 0.3408| 0.9381       | 0.2256   |
| universal-sentence-encoder         | 0     | 0.9344   | 0.3153| 0.9381       | 0.1770   |
| universal-sentence-encoder-large   | 0     | 0.9365   | 0.2923| 0.9381       | 0.1682   |


This table provides a quick overview of the training results for each model, including accuracy, loss, and validation metrics.

# Summary of Training Results

- The models were trained for one epoch each.
- The accuracy of the models ranged from 92.13% to 93.65%.
- The loss values varied between 0.2729 and 0.3408.
- All models achieved a validation accuracy of 93.81%.
- The validation loss ranged from 0.1682 to 0.2256.

This summary provides a concise overview of the training performance across different models.
