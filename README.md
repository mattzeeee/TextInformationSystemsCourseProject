# CS 410 Text Information Systems 
# Final Course Project 
# Team: The Classifiers

# Members
Praveen Pathri (ppathri2@illinois.edu)
Steven Piquito (piquito2@illinois.edu)
Mattias Rumpf (mrumpf2@illinois.eu) - captain

# Project Topic
Option 4: Text Classification Competition - Sarcasm Detection on Twitter data

# Project Setup and Individual Contributions
The submitted work represents a well balanced team effort: Each of the members spend considerable time on researching potential models and frameworks. Praveen and Steven worked on and tested baseline models like SVM and random forest, Matthias focused on pre-trained models. When BERT type models turned out to be the most promising, we jointly concentrated on improving the performance of a fine tuned RoBERTa model. Praveen looked into improving accuracy via data preparation, Steven added context, Matthias experimented with hyperparameter tuning. 


# Running our Code and replicating results

## Screencast tutorial
Please follow the screencast tutorial which is available at
*   x

## Install instructions
To install all required libraries we assume that users have a recent install of the Anaconda distribution with Python <=3.7 
* Open Anaconda Navigator and create a new python 3.7 environment
* Install and open the Anaconda App "cmd prompt", check that the newly created environment is activated
* go to https://pytorch.org/get-started/locally/ and get your install command <br>
e.g. conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch <br>
or without cpu conda install pytorch torchvision torchaudio cpuonly -c pytorch
* run the install command in the cmd prompt
* enter in cmd prompt: pip install simpletransformers jsonlines pandas transformers nltk torch
* cd to your working directory e.g.: cd C:\UIUC\TextMining\FinalProjectSubmission
* then start notebooks by entering n cmd prompt: jupyter notebook

## Main document: Project Report Team The Classifiers - Twitter Sarcasm Detection (with a fine-tuned RoBERTa model)
To replicate our results run the following notebook
* Jupyter Notebook 
* PDF

## Appendix I.The progress report - initial experimentation
* Jupyter Notebook see "Appendix I.The progress report - initial experimentation.ipynb"
* PDF see "Appendix I.The progress report - initial experimentation.pdf"
## Appendix II. Hyperparameter tuning
* Jupyter Notebook see "Appendix II. Hyperparameter tuning.ipynb"
* PDF  see "Appendix II. Hyperparameter tuning.pdf"