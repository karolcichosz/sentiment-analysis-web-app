# Sentiment Analysis Web Application Overview

This web app predicts if provided review is **positive** or **negative**. So exemplary outputs are presented in the `output` directory.

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network (RNN) performing sentiment analysis on movie reviews. This project implements Sentiment Analysis (Binary Classification problem) using Word Embedding layer, LSTM layer, Dense layer and sigmoid function.



## Installation

You need [Amazon Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html) and a [Notebook instance](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html) to run this code. While creating a Notebook instance you can add link to this [repository](https://github.com/karolcichosz/project-plagiarism-detection.git), so can can have this project placed in your Notebook instance. You will also need [AWS Lambda](https://aws.amazon.com/lambda/) and [Amazon API Gateway](https://aws.amazon.com/api-gateway/), to create model endpoint and make it avaliable to html website, but
all step by step detailed instructions are provided in Jupiter Notebook _SageMaker Project.ipynb_.

## Licence

Copyright: [Karol Cichosz](https://www.linkedin.com/in/karolcichosz/): The content of this repository is licensed under [MIT licence](https://choosealicense.com/licenses/mit/).
