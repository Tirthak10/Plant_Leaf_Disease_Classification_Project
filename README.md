# Plant_Leaf_Disease_Classification_Project
The Plant Leaf Disease Detection project utilizes deep learning techniques to identify and classify common diseases affecting plant leaves, specifically Black Spot and Powdery Mildew. This system offers an automated and efficient solution for early disease detection, reducing reliance on manual inspection and enabling timely interventions for farmers and agricultural stakeholders. The model is built using a Convolutional Neural Network (CNN) architecture, consisting of multiple convolutional layers for feature extraction, followed by fully connected layers with dropout to mitigate overfitting.

->Disease Classification: The model is trained to classify two common plant leaf diseases: ->Black Spot (bs) ->Powdery Mildew (pm)

->About the Dataset: The dataset comprises three folders (train, valid, and test), each containing images labeled based on their disease type. Images are categorized into:
  1)Training set: Used to train the model.
  2)Validation set: Used to tune hyperparameters and monitor performance during training.
  3)Test set: Used to evaluate the model's performance on unseen data. Dataset Link: https://universe.roboflow.com/jaymoh/plant-diseases-vmkpn

->Technologies Used: Programming Language: Python Deep Learning Framework: TensorFlow/Keras Data Preprocessing: TensorFlow Image Processing Utilities Visualization: Matplotlib Evaluation Metrics: Accuracy, Loss, Classification Report (Precision, Recall, F1-Score)

->Model Architecture: The model employs a Convolutional Neural Network (CNN) architecture with the following layers:
  1)Three convolutional layers with ReLU activation and MaxPooling for feature extraction.
  2)A fully connected dense layer with a dropout rate of 50% to reduce overfitting.
  3)An output layer with a softmax activation function to predict probabilities for two classes.

-> Project Applications:
  1)Early detection of plant diseases to reduce crop loss.
  2)Integration into agricultural support systems to aid farmers in decision-making.
