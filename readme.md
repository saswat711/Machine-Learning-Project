# This repo contains some of the machine learning projects I have developed from predictions, to classifications

# Some of the projects in the repo are currently under development

**I have used Tensoflow and Keras workplace and API and have developed it in Google Colab**

**I have used kaggle for the datasets for the projects**

# Admission Prediction:

 In this project I made an ML Model which takes your 'GRE Score',	'TOEFL Score',	'University Rating',	'SOP',	'LOR',	'CGPA',	'Research' as training parameters. I have used keras sequential modeling to create layers for the model. 

 The metrics of the trained model are loss: 5.8119 - mae: 2.4064 - mse: 5.8119

# Jaipur Tourism:

 This project is still under development. Here we are trying to build a hotel, places recommendation in jaipur based on the user requirements like finance, to location, to type of places they want to visit.

# Sentence Grammatically correct or not:
 I have used pytroch and Bert transformer to create the model. Initially started with tokenizing the sentences.

 Then used Bert for sequential classification of the text. The model is than optimized using: optimizer = AdamW(model.parameters(),
                  lr = 2e-5, # args.learning_rate - default is 5e-5, our notebook had 2e-5
                  eps = 1e-8 # args.adam_epsilon  - default is 1e-8.
                )

 The trained models have following metrics:  Accuracy: 0.85
  Validation Loss: 0.44
  Validation took: 0:00:06
 
# Simposons Detection:

  I have created an sequential CNN model here. 
  The model have following metrics for compilation: >For optimizer = RMSprop(lr=0.001, decay=1e-6),
  loss = "categorical_crossentropy", metrics="accuracy"

  The trained model have following results: Simpson characters were predicted with a loss of 0.09837 and an accuracy of 97.78%

# Square and Circle Classifier:
   
   I have created an input function thorugh which user can attach link to any circle and square image and the model will be able to predict it.
   
   I have create a CNN sequential model using tensorflow Keras and have compiled it with following metric optimizer='adam', loss='binary_crossentropy', metrics='accuracy'

   The trained model results are: loss: 0.1237 - accuracy: 0.9570 - val_loss: 4.7584 - val_accuracy: 0.5000

# Refrences:

  * For simpsons: https://www.dsimb.inserm.fr/~ghouzam/personal_projects/Simpson_character_recognition.html

  * For Bert: https://analyticsindiamag.com/how-to-use-bert-transformer-for-grammar-checking/

  **Link to datsets** 

  * [Simpsons Character Data](https://www.kaggle.com/datasets/alexattia/the-simpsons-characters-dataset)

  * [Square vs Cirle Data](https://raw.githubusercontent.com/saswat711/Machine-Learning-Project/main/Square%20and%20Circle%20Classifier/dataset.zip)

  * [Jaipur Tourism Data](https://github.com/saswat711/Machine-Learning-Project/tree/main/Jaipur%20Tourism)

  * [Senetence Grammatically Correct using Bert](https://github.com/saswat711/Machine-Learning-Project/tree/main/Sentence%20Grammatical%20Correct%20or%20Not)

  * [Admission Prediction Data](https://github.com/saswat711/Machine-Learning-Project/tree/main/Admission%20Predictions)
