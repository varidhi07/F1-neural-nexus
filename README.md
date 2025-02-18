# F1-neural-nexus
## problem statement
### objective
to develope a mchine learning model that predicts whether an F1 driver would obtain podium position depending on the following criteria:<br />
  points, <br />
  laps, <br />
  fastest speed, and<br />
  grid.<br /> 
### description
the dataset contained the following necessary columns<br />
1, raceId<br />
2. year<br />
3. round<br />
4. circuitId<br />
5,  grid<br />
6. position<br />
7. points<br />
8. laps<br />
9. fastestLapSpeed<br />
10. driverId and driver_name<br />
11. constructorId<br /><br />
using these parameters the data was analysed and visualised then several models were used to train and predict values in the data(podium column being the target that was created using the position column), out of these models one with the highest accuracy has to be chosen for the final project.
<br />
## summary and result
the data was cleanes then analysed and then finally normalised to get it ready to be split according to target and feature columns. this split data was further divided for training and testing<br />
now different models(namely SVM, Logistic Regressor, and  Random Forest Classifier) were applied and their accuracy noted, the output being:<br /><br />
Logistic Regression: 0.8245<br />
Random Forest: 0.9048<br />
SVM: 0.9074<br /><br />
hence SVM was chosen as the model best for for training< which also gave the following results:<br />
|        | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| **0**       | 0.88      | 0.92   | 0.90     | 2425    |
| **1**       | 0.93      | 0.90   | 0.91     | 2879    |
| **Accuracy** | -        | -      | 0.91     | 5304    |
| **Macro Avg** | 0.91    | 0.91   | 0.91     | 5304    |
| **Weighted Avg** | 0.91 | 0.91   | 0.91     | 5304    |





