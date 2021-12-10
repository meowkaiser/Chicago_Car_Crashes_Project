# Chicago Car Crashes
## Overview
We used Chicago,IL car crash data from city of Chicago website the 3 data sets contain crash info, info on people involved and info on vehicles involved.


We used the 3 data sets below from the City of Chicago website and combined them.


Traffic Crashes - Crashes: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

Traffic Crashes - Vehicle: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3

Traffic Crashes - People: https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d

slides: https://docs.google.com/presentation/d/1i6e1qaAa6ln5N2bog0SUE1Iu5o6FDZp6ia87A796xgs/edit#slide=id.g10644cfca8a_0_147

## Business and Data Understanding

We started a software company to help car companys make their buyers feel safer. We are pitching the product to Mercedes Benz because they are a world reknown symbol of quality and class. The software is used to potentially save the life of a driver in the event of a car accident. Similar to that of a black box, the software takes record of the features occuring at the time of the accident and if they are highly correlated with those of previous fatal crashes, athorities are immediately notified of possible death. We created classification models to predict what the prime factors cause an accident that can result in a fatality. If successful and Mercedes Benz implements our recommendations, we will see a decrease in fatalities and an overall increase in safety for all citizens.

## Modeling

![image](https://user-images.githubusercontent.com/12703065/145256200-6a319729-69fd-461e-9384-b18728d99d07.png)
We chose to use dummy, dummy with smote, decision tree, random forrest and k-nearest neighbor for our modeling. K-nearest neighbor was not a good modeling choice for our data because we have entirely too much data so it had to be taken out of our final product. 

## Evaluation

![image](https://user-images.githubusercontent.com/12703065/145587882-e859575d-6639-4ffc-921c-b6b9dc063155.png)
Decision Tree:
* Accuracy:  0.9180
* AUC: 0.79
* Precision: 0.0079
* Recall: 0.4884
* F1 Score: 0.0155

This final model is excellent at predicting whether or not a car crash is fatal. Therefore, this model should be used by car companies as a safety feature in their vehicles to help 911 dispatchers determine whether or not certain crashes are a priority or not.

## Conclusion
We conclude that Mercedes Benz should have software follow the decision tree model, use those recommendations to determine emergency and install “smart” software on cars that use this model.
