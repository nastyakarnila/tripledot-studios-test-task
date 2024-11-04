Tripledot Studios Test Task project


Test cases for the data analyst:

1) Prediction task.
	There is data on the cohort of users who perform a certain action in the application:

	day,share
	0,0.7123
	1,0.2279
	2,0.1883
	3,0.1758
	4,0.1598
	5,0.1559
	6,0.1459
	7,0.1373
	10,0.115
	14,0.1026
	17,0.0994
	21,0.0907
	24,0.0838
	28,0.0837

	You should:
	1.1) find the optimal approximating function for future values prediction and write down the formula for this function with optimized coefficients.
	1.2) visualize the initial data on the plot, as well as the values of the approximating function in the range from 0 to 120 days.


2) Probability theory task.
	There are 5 dices in the pot (4-sided, 6-sided, 8-sided, 12-sided, 20-sided). The player randomly selected a dice, tossed it and the value 5 shown on it. It is necessary to determine the probability for each of the 5 dices that it was chosen.

	P.S.: A 20-sided dice is a dice that has 20 faces with values from 1 to 20.
	
3) The analyzing task of the results of the A/B test.
	The results of the A/B test are saved in the file "experiment_data.csv". It is necessary to analyze whether there is a statistically significant difference in the analyzed metric between the two variants.
	You should:
	1) to justify the chosen method of the analysis;
	2) demonstrate the Python code for the analysis (for example in Jupyter Notebook, etc.); 
	3) explain the results of the analysis
