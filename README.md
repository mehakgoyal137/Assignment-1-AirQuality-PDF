# Assignment-1-AirQuality-PDF

Description
For this assignment, I wrote a Python script to analyze the air quality data (NO2 levels). The task was to transform the data based on my university roll number and then estimate the probability density function (PDF) parameters.

Steps I Followed

1. Data Loading: 
   I loaded the 'data.csv' file and selected the 'no2' column. I dropped the empty rows to make sure the data was clean.

2. Transformation: 
   I transformed the original NO2 values (x) into a new variable (z) using the formula given in the assignment:
   
   z = x + ar * sin(br * x)

   My Roll Number is 102303724. Based on this, I calculated the constants:
   - ar = 0.25
   - br = 1.5

3. Finding Parameters: 
   To find the curve that fits this data, I calculated the Mean and Variance of the transformed data (z). Using these, I found the three required parameters: Lambda, Mu, and c.

Final Results
These are the values I got from my code and submitted in the Google Form:

- Lambda: 0.0014617052940514906
- Mu: 25.818063543032295
- c: 0.021570239817484047

Result Graph
I have attached the graph below. The blue part is the histogram of my data, and the red line is the PDF curve I calculated.

![Result Graph](result_graph.png)
