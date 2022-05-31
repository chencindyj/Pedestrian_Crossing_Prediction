# Pedestrian_Crossing_Prediction
Use Recurrent Neural Networks to analyze annotated video sequences to predict pedestrian crossings 

# Brief Overview
My machine learning problem of interest is the ability to predict whether a pedestrian will cross the street in front of a vehicle based on footage from self-driving vehicles. I selected this specific problem for its salient and serious nature: the growing adoption of computer vision technology for self-driving cars heightens the risk of pedestrian casualties and injuries, especially when the technology is still nascent. The critical consequences of an autonomous vehicle hitting even a single pedestrian demands acute attention to pedestrian safety. Accordingly, the ability to accurately predict whether someone is crossing the street in front of a self-driving car is extremely important. When I was given this question for an internship applications's technical evaluation, I hadn't worked with sequential data for classification at the time. Accordingly, I would like to re-approach this classification problem with my newly-acquired knowledge of Recurrent Neural Nets (RNNs).

# Major Steps Involved
* Unnest data from the Joint Attention in Autonomous Driving (JAAD) project from York University
* Strategize on preprocessing data to create different video sequences suitable for training on RNN architectures
* Experiment with various layers including LSTMs, GRUs, and Bidirectional layers
* Apply Keras Tuner to find best hyperparameters
* Evaluate five (5) models and comment on the overall performance of the prediction project
