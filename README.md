# Predicting_Success_all_Rounds_NHL

Models do not do a good job at predicting those players who had a career of 200 games or more. 

See below example of the confustion matrix for model 9. The model only predicted someone would play 200+ games accurately 9 times. 
![Alt text](Confusion%20Matrix%20-%20model%209.png)


Models - shown through pickle files 

Model 1
- SVC, 3 - shoots, prospect category

Model 2 
- SVC, 3 -  North American skater, European Skater, January birth month

Model 4 
- SVC, 6 - prospect plus/minus, February birth month, March birth month, April birth month, June birth month, postion (defense) - 0.77

Model 5
- SVC, 6 - prospect plus/minus, equivalent goals, equivalent assists, offesnive goals vs threshold., overall goals vs threshold, position (defense) - 0.77

Model 6 
- SVC, 4, prospect plus/minus, equivalent goals, equivalent assists, overall goals vs threshold - 0.78

Model 7 
- random forest, 4 - prospect plus/minus, equivalent goals, equivalent assists, overall goals vs threshold - 0.74 

Model 8 
- random forest, 5 - prospect plus/minus, equivalent goals, equivalent assists, offensive goals vs threshold, overall goals vs threshold - 0.76

Model 9 
- Logistic Regressiong, 4 - prospect plus/minus, equivalent goals, equivalent assists, overall goals vs threshold - 0.78