# Assessing-impactful-words-from-short-texts-in-Visual-Media
With the rapid development of Internet technology, the amount of textual data in Visual media such as social media platforms, news platforms is growing rapidly, generating a large amount of textual data. Most companies use advertisements on social media platforms or other websites to improve their business. Most of these contain one-liner sentences with much meaning. Our model helps these companies find the words that can impact users or gain the users' attention. If the model can predict and recommend the essential words or words to be emphasized in the text effectively and accurately, the companies might improve their business even without additional advertisements. In this paper, I have researched and implemented a model that does the task with better accuracy using BERT or ERNIE compared to the classical machine learning models. I have also found that data augmentation and additional feature engineering can help improve performance.
<br/>
### Language used:
Python
<br/>
### Tools used:
Google Colab
### packages
* sklearn
* numpy
* torch
* transformers
* math
### Instructions to run code/Installation
Assessing_short_texts_importance.ipynb file is a colab notebook.
<br/>
<br/>
1.To run the notebook make sure the runtime is selected to GPU.
<br/>
<br/>
2.Install transformers library
```bash 
pip3 install transformers
```
3.Install torch library
```bash 
pip3 install torch
```
4.Install numpy library
```bash 
pip3 install numpy
```
Make sure to change the TRAINING_FILE<TESTING_FILE and DEV_FILE pointing to the files from the "Dataset" folder.
Run all the cells.
### Usage
I have assigned 6 epochs and each epoch takes nearly 40 minutes. so, once the code runs, model predicts the top 5 words of the each senetence from the input data.
The sample output is shown below:
