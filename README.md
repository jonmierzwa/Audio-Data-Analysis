# Audio-Data-Analysis
- Objective: Build 1-D and 2-D CNN classifiers for environmental sound classification problem.
- Dataset: UrbanSound 8k audio data consisting of about 8,700 clips comprising 10 different possible classes.
- Approach: Load in data from CSV file, preprocessing to ease interaction between models with data, feature extraction, model building, comparative analysis, and future steps.
- Key Findings: Overall, the 2-D CNN performed better and yielded an accuracy rate of 78.26%, while the 1-D CNN only achieved 42.77% accuracy. The 1-D CNN struggled to successfully identify Class 0 audio files, but the 2-D CNN did much better identifying Class 0 audio files. Across the board, the 2-D CNN was able to generalize and perform better than the initial 1-D CNN. To improve performance, future work could include adding additional convolutional layers to the CNNs or combining the two models (1-D and 2-D CNN making up one model).
