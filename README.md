# CS-267-Final-Project

## Names
- Jianfan Huo
- Yunhao Du
- Yuchen Wang

## Introduction
Our project aims to create an efficient and accurate spam classification model that will significantly enhance the filtering capabilities of messaging platforms. With the exponential growth of online communication, the number of spam messages has become a serious issue, leading to stress and potential safety for users. To address this challenge, we use the power of modeling data with a probabilistic programming language. Our model considers specific words within messages as conditional parameters for classification. We also put some specific words within the message to our model as the conditional parameter for classification. The dataset will include approximately 87\% non-spam and 13\% spam messages. We split the 80\% dataset into training and the 20\% dataset into tests to ensure unbiased evaluation. During the training process, we construct a vocabulary table, which will include words commonly associated with spam, such as "call" and "claims." These words are the crucial features for training our model to accurately identify the spam message. After the training is complete, we check if it achieves a predetermined baseline of accuracy. We also use the Problog to refine the model's predictions and further improve its efficiency.

In our implementation, we utilized Python for tasks such as data cleaning, model construction, and precise value calculations. For testing our hypotheses and refining the model, we used Problog. The Problog code was written in Python, allowing viewers to directly execute the code using Python. The running code is in the file("CS267A_final.ipynb"). You can also check the "CS_267A_Project_Final_Write_Up.pdf" in the Project pdf File. 

