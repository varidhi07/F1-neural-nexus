# F1-neural-nexus
## problem statement
### objective
to develope a mchine learning model that predicts whether an F1 driver would obtain podium position depending on the following criteria:<br />
  round, <br />
  total pit stops<br />
  total pit time<br />
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
Logistic Regression Accuracy: 0.6613876319758673<br />
Random Forest Accuracy: 0.6734539969834088<br />
SVM Accuracy: 0.691553544494721<br />

hence SVM was chosen as the model best for for training<br />

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.78      | 0.44   | 0.57     | 2425    |
| 1     | 0.66      | 0.89   | 0.76     | 2879    |

**Accuracy:** 0.69  

| Metric       | Score |
|-------------|-------|
| Macro Avg   | 0.72 / 0.67 / 0.66 |
| Weighted Avg | 0.71 / 0.69 / 0.67 |




