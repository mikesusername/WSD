# WSD
Word sense disambiguation
In the jupyter notebook, a word sense disambiguation (wsd) model is built. This function is designed to take two nouns and an adjective as input and the function predicts whether the context of the adjective is likely the same or different when paired with each noun. For example, consider the adjective "hot" and the nouns "woman" and "stove". When we hear "hot woman", we likely infer hot means attractive, and when we hear "hot stove" we infer that hot refers to temperature. Thus, hot is used in different contexts for the nouns "woman" and "stove." This is what the model is designed to predict.

The model was trained and tested on a labeled dataset of 5758 samples, and obtained over 91% accuracy. Whereas, a Lesk algorithm based model only achieved around 50% (no better than random guessing).
