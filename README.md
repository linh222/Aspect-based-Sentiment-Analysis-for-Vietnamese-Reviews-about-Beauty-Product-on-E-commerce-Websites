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

## Publication
The 36th Pacific Asia Conference on Language, Information and Computation (PACLIC36)
Link: https://aclanthology.org/2022.paclic-1.84/

Please cite this paper at:

    @inproceedings{tran-etal-2022-aspect,
    title = "Aspect-based Sentiment Analysis for {V}ietnamese Reviews about Beauty Product on {E}-commerce Websites",
    author = "Tran, Quang-Linh  and
      Le, Phan Thanh Dat  and
      Do, Trong-Hop",
    booktitle = "Proceedings of the 36th Pacific Asia Conference on Language, Information and Computation",
    month = oct,
    year = "2022",
    address = "Manila, Philippines",
    publisher = "De La Salle University",
    url = "https://aclanthology.org/2022.paclic-1.84",
    pages = "767--776",
    }


