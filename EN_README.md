# Inappropriate Content Dataset

## Introduction

This project aims to build a high-quality dataset of inappropriate content to support automated detection models. With the rapid growth of the internet, inappropriate content has become a widespread issue, posing challenges to various online platforms. By creating this dataset, we hope to leverage machine learning techniques to help developers automatically identify and filter harmful content, thus promoting a healthier and safer online environment.

We invite developers and contributors from all backgrounds to participate and contribute to this dataset, helping to improve the project and drive its progress.

## Data Format

To ensure the dataset's consistency and usability, we request that all contributed data follow the structure outlined below:

- **File format**: CSV (Comma-separated values)
- **Columns**:
    1. **Content** (Text type): This column should contain the user-generated content.
    2. **Is Inappropriate** (Integer type): This column marks whether the content is inappropriate, with `1` indicating inappropriate content and `0` indicating non-inappropriate content.

### Example:

| Content | Is Inappropriate |
| --- | --- |
| "This game is terrible!" | 0 |
| "You're such an idiot, worthless!" | 1 |
| "Keep up the good work, I support you!" | 0 |

> Please ensure that the data is accurate, especially when labeling the "Is Inappropriate" column. Correct labeling is crucial for training an effective model.
> 

## Data Requirements

1. **Content**: The content should be realistic and reflect the typical language users may use on various platforms. It can be sourced from social media, comment sections, forums, etc.
2. **Definition of Inappropriate**: "Inappropriate" refers to content that clearly violates social norms, laws, or platform policies, such as insults, hate speech, threats, explicit material, racial discrimination, political sensitivity, etc. The definition can be adjusted based on platform-specific needs.
3. **Diversity**: To improve the generalization of the model, the dataset should contain a variety of content, covering different contexts, language styles, and types of inappropriate content.

## How to Contribute

1. Prepare your data, ensuring it meets the format requirements outlined above.
2. Submit the data file (in CSV format) to the `data` folder of this project, or submit a pull request.
3. If you have multiple datasets, you can distinguish them using naming conventions (e.g., `dataset_v1.csv`).
4. For large datasets, consider submitting the data in batches to make it easier for us to process and integrate.

## Project Goal

The ultimate goal of this project is to help developers create an efficient, accurate automated system for detecting inappropriate content. This system will automatically identify and filter harmful content, reducing the burden on manual moderation and improving the overall quality of online platforms. With your contributions, we aim to build a free, open-source detection tool that can benefit developers and platforms worldwide.

## Thank You

We sincerely thank every contributor! Your effort will help improve the health of online communities. In future versions, we will continue to refine the dataset and make improvements based on feedback. If you have any suggestions or comments about the project, feel free to reach out through Issues or pull requests.
