# spaCy_NLP

![Spacy](data:image/png;base64,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)

This is practice and code template from a tutorial given in https://www.youtube.com/watch?v=WnGPv6HnBok&amp;list=PLBmcuObd5An559HbDr_alBnwVsGq-7uTF
The Dataset for Data Exploration is taken from Kaggle (https://www.kaggle.com/stackoverflow/stacksample).
