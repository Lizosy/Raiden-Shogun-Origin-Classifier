# Raiden Shogun Origin Classifier👾

- [Hugging Face space](https://huggingface.co/spaces/Lizsory/Raiden-Shogun-Origin-Classifier)
- [Hugging Face Repo](https://huggingface.co/spaces/Lizsory/Raiden-Shogun-Origin-Classifier/tree/main)
## Inspiration
This project was inspired by the work done in the repository [Detecting AI-Generated Fake Images](https://github.com/nogibjj/Detecting-AI-Generated-Fake-Images) by nogibjj. The approach and methodologies explored  in this project provided valuable insights and formed a foundationd basis for the development of the Raiden Shogun Origin Classifier. We aimed to dbuild upon these idea and adapt them specifically for
distinguishing AI-generated and human-created images of Raiden Shogun, showcasing the practical applications of learning in the realm of image classification.

## Introduction
Raiden Shogun Origin Classifiern is a project that navigates the intersection of AI and anime. By scraping AI-generated anime images from Pixiv using the [PixivBatchDownloader](https://github.com/xuejianxianzun/PixivBatchDownloader) and comparing them with human-created ones, this project aims to train a machine learning model to recognize and differentiate these two types of artwork.

## Project Components
- **Pixiv Image Scraper**: We harness the PixivBatchDownloader to accumulate a rich dataset of anime images, annotated based on whether they are AI-generated or human-created.
- **Machine Learning Model**: Using Google Colab, we develop an AI model that learns from the dataset. The model's goal is to classify images accurately into their respective origins.

## Data Collection and Cleaning
Data scraping is performed via the PixivBatchDownloader, which is configured to distinguish between 'ai' and 'non-ai' tagged images. Data cleaning is an integral part of the process, ensuring that the model is trained on high-quality and relevant images only.

## Visualization and Analysis
After training, visualize the model's performance using confusion matrices, ROC curves, and other relevant metrics. This will help in understanding the model's strengths and areas for improvement.

## Results🔮

![image](https://github.com/Lizosy/AnimeImageScrapeNLearn/assets/61643547/55e0e2db-458b-4c69-a5ed-783c26b5c2a2)



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


![image](https://github.com/Lizosy/AnimeImageScrapeNLearn/assets/61643547/1d200542-dafc-4b3b-acf3-f4c6c0a6294c)


## Todo
Moving forward, the project aims to:
- Increase the dataset size for better model generalization.

