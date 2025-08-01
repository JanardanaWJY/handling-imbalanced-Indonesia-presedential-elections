# Primary Dataset – Indonesian Elections

This dataset supports the research titled:  
**"Evaluating Knowledge Distillation for Handling Data Imbalance in IndoBERT Sentiment Analysis for Indonesian Elections"**, authored by the contributors of this repository.

## Dataset Description

The dataset consists of tweets related to the Indonesian presidential elections. The data were crawled independently by the authors, initially collecting approximately 12,000 raw entries. After manual filtering and preprocessing, the final dataset contains 10,000 tweets. This reduction was intentionally performed to produce an imbalanced label distribution suitable for the research objectives.

All entries have been manually labeled for sentiment.

### Columns:
- `tweet`: the original tweet content
- `label`: manually assigned sentiment label

### Label Format:
- `1.0` = Negative sentiment  
- `0.0` = Positive sentiment

### Label Distribution:
- Positive: 22.6%  
- Negative: 77.4%

## Usage Notes

This dataset is publicly available for research and educational purposes. Users are welcome to use, analyze, or adapt the dataset **responsibly** and with **proper attribution**. 

Please note that all preprocessing and manual annotation were carried out by the authors to ensure consistency and alignment with the research objectives. Misuse or misrepresentation of the dataset is strongly discouraged.
