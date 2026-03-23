# Applied Deep Learning — Assignment (8pm - 12th May)

## Part 2: Simple Age Estimator (50%)
**Dataset:** [Facial Age — Kaggle](https://www.kaggle.com/datasets/frabbisw/facial-age)

**Data prep:**
- 10% held out test set
- Train/validation split from remainder
- CSV with ages + age with category labels

**Tasks - all from scratch CNNs, no pretrained models:**
- Regression (predict exact age) and Classification (age category)
- CNN kernel variations (activations, kernel sizes)
- Network variations (depth, pooling, skip connections, FC layers)
- Dataset variations (1ch vs 3ch, data augmentation)
- One custom variation of your choice
- Save top 2 models for demo

## Part 3: Backbone Models & Fine Tuning (45%)
- Split non test data into Block 1 and Block 2
- Train autoencoder on Block 1
- Transfer learning from autoencoder → age classification on Block 2
- Fine-tune pretrained ImageNet model → compare to handmade models
