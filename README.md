# image_caption_multi-label_classification

## COMP5329 Deep Learning - Assignment 2
### 15 Apr 2021 - 31 May 2021


The aim of this study is to apply deep learning algorithms that could achieve high performance to classify images based on image information and caption into multiple labels. (The size of the model required less than 100MB.)


Applied fusion techniques to combine a pre-trained image-based classification model EfficientNet-B4 with a text-based classification model Bi-LSTM to make the classifier gain information from both image and caption contents.

Achieved a mean F1-score of approximately 90 within a reasonable amount of time and the final model size is 80.1MB. This project obtained a High Distinction mark.(98/100)








## Code Instructions
There are four Python notebook files:
1. Best_Model_Full_Version.ipynb
2. Best_Classifier_Model.ipynb
3. Best_Image_Model_EffNetB4.ipynb
4. Best_Text_Model_Bi_LSTM_5329A2.ipynb

The "Best_Model_Full_Version.ipynb" file can automatically download the relevant models which are pre-trained in the other three files.

Please run the code with the following steps:
1. Upload the "Best_Model_Full_Version.ipynb" file to the Google Colab and open it.
2. Click "Run all" in the "Runtime" tab or press "cmd/Ctrl+F9" to run code blocks from the beginning.
3. In the "load and process dataset" section under the "Preparation" section, click the given link and follow the instruction to sign in to your Google Account, then copy and paste the google verification code back to the input area, the whole dataset will be downloaded and imported automatically.
4. The following sections will be run automatically and the running process should be completed within approximate 50 minutes. After that, you supposed to see the generated CSV file with predicted labels called "Predicted_labels.csv" in the "Files" area which is on the left-hand side.
