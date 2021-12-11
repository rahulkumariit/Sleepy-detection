# Sleepy-detection
A CNN based approach to detect whether a driver is feeling sleepy or not while driving.

Problem Statement
DETECTION OF WHETHER A PERSON IS YAWNING OR NOT AND HIS EYES ARE CLOSED OR NOT USING CNN to FINALLY DETECT WHETHER HE/SHE IS SLEEPING OR NOT

The NHTSA estimates that 50,000 injuries and nearly 800 deaths happens every year due to 91000 crashes involving sleepy drivers and this is due to the fact that a driver who falls asleep at the wheel loses control of the vehicle which often results in a crash with either another vehicle or stationary objects.

In addition to this, a report of AIIMS Neurology India suggets that sleepiness in drivers became the reason behind more than 20% of all road accidents. This is not the problem only with normal car drivers rather it also happens in case of truck drivers and HEMM (Mining vehicles) operators. In mining, due to the sleepy condition of some HEMM operators (Especially those who work in 12 hr shift), the cycle time of material extracted also gets increased which further results in overall loss of hundereds of thousands of ruppes in a single day.

Because of this serious problem, we will develop a CNN here that can detect if eyes of a driver are closed or not along with whether the driver is yawning or not while driving. When applied in real time it will give audio as well as visual alert to avoid any accident. This sort of technology is useful for anybody interested in increased driving safety, including commercial & everyday drivers, car companies, and vehicle-insurance companies. Hence, this notebook presents a solution for sleepy driver detection using a Convolutional Neural Network with less than 3.5M trainable parameters for easy deployment on edge or computationally less efficient devices. As a result, the driver can be alerted at the right time if the system detects that the driver has fallen asleep before anything dangerous happens.

Approach -------
  Data downloading and understanding,
  Reading, Splitting (into training and test set) and Analyzing the data,
  Pre - processing of data,
  Creating features in the form of numeric data from the images,
  Modelling and training,
  Checking accuracy ( with confusion, recall and precision matrix ) and,
  Prediction - With still images, with webcam and real time
  
I have collected data from Kaggle.
Link - https://www.kaggle.com/dheerajperumandla/drowsiness-dataset


Google drive link for the data -  https://drive.google.com/drive/folders/1Q8SJQUJCbl4IouNKMNAGujUFJyg_IQEN?usp=sharing

Google drive link for the presentation video - https://drive.google.com/file/d/1xQg68g5evey59kgh42ACtBj0YwfYPeXs/view?usp=sharing
