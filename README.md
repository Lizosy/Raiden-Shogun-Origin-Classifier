# AnimeImageScrapeNLearn

## Introduction
AnimeImageScrapeNLearn is a project that navigates the intersection of AI and anime. By scraping AI-generated anime images from Pixiv using the [PixivBatchDownloader](https://github.com/xuejianxianzun/PixivBatchDownloader) and comparing them with human-created ones, this project aims to train a machine learning model to recognize and differentiate these two types of artwork.

## Project Components
- **Pixiv Image Scraper**: We harness the PixivBatchDownloader to accumulate a rich dataset of anime images, annotated based on whether they are AI-generated or human-created.
- **Machine Learning Model**: Using Google Colab, we develop an AI model that learns from the dataset. The model's goal is to classify images accurately into their respective origins.

## Usage
To utilize this project for your own research or interest, you can:

1. Clone this repository to your local machine or Google Colab environment.
2. Follow the installation and setup instructions in the [PixivBatchDownloader repository](https://github.com/xuejianxianzun/PixivBatchDownloader) to begin collecting your own set of images from Pixiv, making sure to filter for 'ai' and 'non-ai' tags as needed.
3. Once you have collected the images, use the notebooks provided in this repository to train and validate your machine learning model.

## Data Collection and Cleaning
Data scraping is performed via the PixivBatchDownloader, which is configured to distinguish between 'ai' and 'non-ai' tagged images. Data cleaning is an integral part of the process, ensuring that the model is trained on high-quality and relevant images only.

## Visualization and Analysis
After training, visualize the model's performance using confusion matrices, ROC curves, and other relevant metrics. This will help in understanding the model's strengths and areas for improvement.

## Acknowledgements
Special thanks to Kaggle and `lizwozsliz` for providing the `data-raiden-shogun` dataset which has been instrumental in the development of our AI model.

## Results
After training the model on the collected dataset, we achieved the following results:

- **AI-Generated Artwork Classification**
  - Precision: 98%
  - Recall: 90%
  - F1-score: 94%

- **Human-Created Artwork Classification**
  - Precision: 69%
  - Recall: 92%
  - F1-score: 79%

- **Overall Model Performance**
  - Accuracy: 91%
  - Weighted Avg Precision: 92%
  - Weighted Avg Recall: 91%
  - Weighted Avg F1-score: 91%


## Todo
Moving forward, the project aims to:
- Increase the dataset size for better model generalization.
- Experiment with more complex models such as Convolutional Neural Networks (CNNs) for improved accuracy.
- Implement additional features like image tagging and reverse image search for enhanced functionality.
- Explore the possibility of real-time classification within a browser extension or a mobile app.

