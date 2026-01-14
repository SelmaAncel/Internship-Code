# Internship-Code
Code used for my internship at Tilburg University.

This repository contains code developed for a project investigating the use of social robots for teaching emotion recognition to individuals with mild intellectual disabilities (ID). The project includes both statistical analyses and machine learning experiments.

The QTrobot (LuxAI, 2025) was used to provide emotion recognition training to the experimental group over a four-week period, while the Furhat robot (Furhat Robotics, 2025) was used to assess each participants' ability ro recognize emotions before and after the first and last training sessions. The Furhat robot was used for the control group as well, at the beginning and end of a four week period. Chi-square tests were used to compare Furhat pre- and post-test performance between the experimental group and control group, to assess whether there is an effect of interactions with a social robot on learning emotion recognition for individuals with mild ID.

In addition, facial key features were collected from seven individuals with mild ID during the QTrobot learning sessions, in which participants were prompted to express sadness, anger and fear. Neutral key features of participants were collected at the start of each sessions. These features were used to train and evaluate five machine learning models to assess their effectiveness in recognizing these four emotions (sadness, anger, fear and neutral). Data collected the first three sessions was used for training, the data collected the last session for training.

**The five models used are:**
- Logistic Regression
- Random Forest
- Multilayer Perceptron
- Support Vector Machine
- K-Nearest Neighbor

Furthermore, during the experiments, participant engagement was assessed with the use of a survey. The scores created from these surveys where compared to the accuracy of the best performing model for each participant with a Pearson Correlation test to assess how well various machine learning models can indicate engagement in individuals with mild ID when interacting with a social robot.

## Setup
The following files are included:
- **General models:** Includes the code for training the five models on the data of the combined key features from the participants.
- **Individual models:** Includes the code for training the five models for each participant individually.
- **Chi-square tests:** Includes the code for multiple Chi-square tests comparing the amount of emotions recognised between the control group and experimental group per.
- **Corelation testing:** Includes the code for correlation testing between model accuracy and participant engagement scores.

## References
- Furhat Robotics. (2025). The world039;s most advanced social robot - Furhat Robotics. 
Retrieved from https://furhatrobotics.com/
- LuxAI. (2025). robot-for-research-development - LuxAI S.A. Retrieved from 
https://luxai.com/product/qtrobot-research-platform/

  
