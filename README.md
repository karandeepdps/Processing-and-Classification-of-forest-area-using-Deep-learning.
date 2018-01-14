# Processing-and-Classification-of-forest-area-using-Deep-learning.

**Version Final**

[Data:](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data)

Class Labels

The class labels for this task were chosen in collaboration with Planet's Impact team and represent a reasonable subset of phenomena of interest in the Amazon basin. The labels can broadly be broken into three groups: atmospheric conditions, common land cover/land use phenomena, and rare land cover/land use phenomena. Each chip will have one and potentially more than one atmospheric label and zero or more common and rare labels. Chips that are labeled as cloudy should have no other labels, but there may be labeling errors. Sample chips with labels
![Sample chips](https://kaggle2.blob.core.windows.net/competitions/kaggle/6322/media/chips.jpg)
Above: Sample chips and their labels.

As discussed in the data collection portion of this document, the chip labels are inherently noisy due to the labeling process and ambiguity of features, and scenes may either omit class labels or have incorrect class labels. Part of the challenge of this competition is to figure out how to work with noisy data.