# Kaggle Projects
This repository contains my personal projects on Kaggle. 
Other general purpose Python projects are also included.
Each project is represented in the Jupyter notebook.

## List of Projects:
1. Spaceship Titanic:
A modification of the famous Titanic dataset problem. The goal is 
to predict who survives or not given a set of feature variables

2. Kaggle 2022 Data Science and Machine Learning Survey:
A dashboard for the Kaggle 2022 survey. I use visualization libraries
to understand the trends, challenges and tools used by data scientists
and machine learning practitioners.

3. Tesla Stock Price Analysis and Prediction with Deep Learning:
In this notebook, we will first perform EDA on the Tesla stock prices dataset to understand the trends and patterns in the data. Next, we will use a LSTM deep learning model to predict future stock prices.

4. Customer Segmentation:
A comprehensive analysis of customer data in a mall with K-means clustering.

5. IMDB Sentiment Analysis:
Contextual Mining on text from IMDB movie reviews.

6. Digit Recognition with Keras:
Building a deep learning model for image recognition of handwritten digits using Keras and the MNIST dataset.

7. Language Translation:
Creating a web app for language translation using the Gradio library and pre-trained translation models from the Transformers library. 

8. FPL Team Builder:
Selecting the best team to place in your fantasy sports team using the `requests` library and performing data augmentation.

9. Sales Prediction:
Making use of statistical models and machine learning to predict sales of various products at a chain of stores.

10. Twitter Data Mining:
Performing contextual mining and topic modelling on my Twitter data.

11. Recommendation Engine:
Building a recommendation engine using Demographic Filtering, Content Based Filtering and Collaborative Filtering.

12. Object Detection with Pytorch:
We perform detection of three different fruits in images using a pretrained Faster R-CNN model with Pytorch.

## Kaggle API 
To access the data remotely, I made use of the Kaggle API which pulls the data directly into Google Colab. You will need to have an account on Kaggle to use the API if you wish to do the same.
If you do, run this code in Colab to upload your Kaggle API key:

```
from google.colab import files
files.upload() # upload kaggle.json

!pip install -q kaggle
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!ls ~/.kaggle
!chmod 600 /root/.kaggle/kaggle.json

!kaggle kernels list — user YOUR_USER — sort-by dateRun
```

## Contributing
If you find any errors or have suggestions for improvements, please feel
free to open an issue or create a pull request.

## License
This repository is licensed under the [MIT License](https://opensource.org/licenses/MIT)
