# matplotlib---pharmaceuticals

<h1>Pharmaceutical Mouse Data</h1>

![bargraph for mice](https://github.com/EmmaLimoli/matplotlib---pharmaceuticals/blob/master/matplotlib_homework/images/Screen%20Shot%202020-07-14%20at%204.38.09%20PM.png)


<strong>The Goal:</strong> The goal of this project was to analyze pharmaceutical data from mice to identify treatments that would be beneficial in cancer treatment. There were 10 different treatments that were used on the mice and I took the top four effective ones to determine the best option.

<strong>How This Was Achieved:</strong>
There were two CSVs that I was given that had the data for the mice and for the study results. I merged these two CSV files on 'Mouse ID.' Once that was complete, I cleaned the data to ensure there were no duplicates. 

After that was complete, I decided to look through the statistics to gain a better understanding of what the data was doing. I used groupby to look at each individual treatment. Once that was complete, I created a dataframe to put the mean, median, variance, standard deviation, and the SEM to analyze. For each of the treatments, I could read the mean, median, variance, standard deviation, and the SEM to determine which one was the most effective. 

To create effective visuals for the data to help tell the story, I used a bar plot and pie graph. There are two bar graphs that were created one by Pandas and the other by PyPlot. Both of the bar plots show the same data (the number of mice per timepoint for the drug treatment) by using two different methods. The pie plot breaks up the female vs. male mice in both of the pie plots, but use two different methods as well (Pandas and PyPlot).

Next, I used quartiles, outliers, and boxplots to better understand the top four drug treatments. I took Capomulin, Ramicane, Infubinol, and Ceftamin and pulled all of the data for the tumor volume (mm3) for each mouse. Looking at this number helped to plot out the quartiles and median to determine what option of drug treatment is best.

Once that was complete, I created a boxplot to look at the drug treatments and create a visualize that could easily be digested. It showed the outliers and the tumor volume for the top four treatments. 

I created scatterplots and a line graph to plot the data. The line graph showed the treatment path for one mouse that used Capomulin. This helped to look at the journey of one mouse's treatment. In the scatterplots, I looked at the weight and tumor volume for mice that were given Capomulin. Capomulin was chosen because it seemed to be the best treatment option.

Lastly, I used correlation and regression to plot the weight and tumor volume of the mice who took Capomulin. I calculated the coefficent to see the relationship between the top drug treatment and how effective it was on the mice. The scatterplot and linear regression was used to show the trajectory of treatment. 

<strong>Conclusion:</strong>
In conclusion, we were able to determine the best treatment out of all of the options for cancer. By analyzing the tumor volume of the mice, we were able to see which option had the biggest impact. It was determined that Capomulin was ideal because it had the greated impact on the mice decreasing their tumor size.

<strong>Observable Trends</strong>

<strong>Observation One:</strong> 
The first observation that can be gathered from the data is Ramicane had the lowest average for the tumor volume size at 40.21. Capomulin had the second lowest average at 40.67. The rest of the treatments have pretty similiar means. This shows us that Ramicane and Capomulin were the most succesful for tumor volume size.

<strong>Observation Two:</strong> 
Capomulin and Ramicane are two comparable drug treatments. Capomulin used 230 mice in the trial and Ramicane used 228. To figure out which treatment would be best for anti-cancer pharmaceuticals, it would be beneficial to compare these two treatments more in depth to further understand the differences.

<strong>Observation Three:</strong> 
The Capomulin method has a correlation between weight and tumor of 0.7088568047708717, which means due to its close proximity to 1, there is a stronger correlation.

<strong>Tools used: Scipy.stats, Pandas, Numpy, Matplotlib</strong>

