# Aspect-based Sentiment Analysis for Vietnamese Reviews about Beauty Product on E-commerce Websites
Predict the aspects and corresponding sentiment in Vietnamese reviews about beauty products (Lipstick) in Shopee
## Description
Input: The text reviews in Vietnamese language.

Output: 1 or N aspect and the corresponding sentiment

List of aspect: [SMELL, COLOUR, PACKING, SHIPPING, STAYINGPOWER, TEXTURE, PRICE, OTHERS]

List of sentiment: [Positive, Neutral, Negative]

Example:

Input: Cây son có màu rất đẹp, còn rất lì nữa (The colour of the lipstick is beautiful, and it is very adhesive too)

Output: COLOUR:Positive, STAYINGPOWER:Positive

## Baseline code
We propose 5 models: BiLSTM, BiGRU, BiLSTM+Conv1D, BiGRU+Conv1D, BiLSTM+BiGRU+Conv1D.
In addition, we implement two approaches for Single-task learning and Multi-task learning

##Publication
In Review

##Data
If you have interested in the problem, please don't hesitate to contact me at 18520997@gm.uit.edu.vn to get the dataset.