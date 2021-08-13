# Assessing-impactful-words-from-short-texts-in-Visual-Media
With the rapid development of Internet technology, the amount of textual data in Visual media such as social media platforms, news platforms is growing rapidly, generating a large amount of textual data. Most companies use advertisements on social media platforms or other websites to improve their business. Most of these contain one-liner sentences with much meaning. Our model helps these companies find the words that can impact users or gain the users' attention. If the model can predict and recommend the essential words or words to be emphasized in the text effectively and accurately, the companies might improve their business even without additional advertisements. In this paper, I have researched and implemented a model that does the task with better accuracy using BERT or ERNIE compared to the classical machine learning models. I have also found that data augmentation and additional feature engineering can help improve performance.
<br/>
![Assessing_short_text_importance.ipynb](https://github.com/Uday-Samineni97/Assessing-impactful-words-from-short-texts-in-Visual-Media/blob/master/Assessing_short_text_importance.ipynb)
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
### Visuals
Here is the code snippet of main model used in this project.
<br/>
![alt text](https://github.com/Uday-Samineni97/Assessing-impactful-words-from-short-texts-in-Visual-Media/blob/main/Model.png)
<br/>
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
You can run the model on any dataset by changing the path of TRAINING_FILE,TESTING_FILE and DEV_FILE to the corresponding input files.
<br/>
The sample output with ground truth probabilities on left and predicted values on right is shown below:
<br/>
<br/>
![alt text](https://github.com/Uday-Samineni97/Assessing-impactful-words-from-short-texts-in-Visual-Media/blob/main/output.png)
### Support
I would be happy to coloborate to work on future enhancements or other improvements.
Interested? Email me at: <udaysamineni2016@gmail.com>
### Future work and enhancements
In this project, I have worked only on the english reviews. I am planning to extend the implementation with reviews from other languages like chineese etc...
