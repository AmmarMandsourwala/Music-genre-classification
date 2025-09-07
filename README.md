# Music-genre-classification
Project Overview
This project aims to classify music tracks into genres by leveraging machine learning techniques. The dataset includes a wide range of musical features, though a large portion of the tracks lack explicit genre labels. To tackle this, Principal Component Analysis (PCA) is applied to reduce the high dimensionality of the data, making it easier to identify hidden structures and patterns.

By transforming correlated features into a smaller set of independent components, PCA helps simplify the dataset, reduce noise, and enhance the efficiency of the classification model. These transformed features are then fed into a Logistic Regression classifier, which predicts the genres of the unlabeled tracks.

The project is designed to highlight the essential concepts of PCA and machine learning in the context of music analysis, while keeping the feature set intuitive and avoiding the need for advanced domain expertise in audio signal processing.

Why PCA?
Music datasets often contain dozens of overlapping features. PCA helps by:
1.) Reducing redundancy among features.
2.) Highlighting key patterns in the data.
3.) Improving classification performance by filtering out noise.

This approach is not only efficient but also widely used in similar research efforts, where PCA has proven valuable for pre-processing features before applying classification or clustering algorithms.
