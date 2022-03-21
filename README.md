# Health_care_entities

A data set is given in which a lot of text is written related to the medical domain. In this dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text.

For example, in the sentence:

“The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”
the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence. The diseases and their treatment are not explicitly mentioned in the dataset, but you have to build an algorithm to map the diseases and their respective treatment and list them out in the form of a table or a dictionary.

In this assignment, you need to perform the following broad steps:

You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.

After that, you need to define the features to build the CRF model.

Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.

Once the features are computed, you need to define the target variable and then build the CRF model.

Then, you need to perform the evaluation using a test data set.

After that, you need to create a dictionary in which diseases are keys and treatments are values.

There are eight major tasks that you need to perform to complete the assignment. They are as follows:

1-Data preprocessing

2-Concept identification

3-Defining the features for CRF

4-Getting the features words and sentences

5-Defining input and target variables

6-Building the model

7-Evaluating the model

8-Identifying the diseases and predicted treatment using a custom NER

