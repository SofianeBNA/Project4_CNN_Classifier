# Project4_CNN_Classifier
contains files about Project4


The goal is to create a CNN CLassifier which will be able to recnogize electronic components. We're using an existing dataset of electronic components found on the net (I'll drop it with the others files). Then we're creating the model with Edge Impulse (with a Image block and A Classifier block). The image block is used for preparing the images before they will be classified (We're filtered them). For the Classifier training, they recommend me to put a number of training cycle between 100 and 200. I've tried with 130 for the first training and it gave me a pretty good confusion matrix (I obtained 92.7 % for accuracy and 0.21 for loss). Scores of each labels are between 80% and 100%. With others improvments such as an drop out layer added as the last layer (that's suggested by the teacher), I got lower results than before and I didnt expected that (I got 87% for accuracy and 0.23 for loss) and the label scores are between 62% (for the resistors, it means the model didnt recnognize correctly the resistor) and 95%. The model testing got 85% for accuracy. 

Finally, I deployed my model into an Arduino and drop it here . 
