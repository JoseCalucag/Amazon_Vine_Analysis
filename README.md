

<h1 align = "center"> Amazon_Vine_Analysis </h1>

<p align = "center">
<img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKZes_QAmSFjPJ1kwI6NEFYGHu_GW3qRRNeg&usqp=CAU"width = "600" height = "300">
 </p>

<h2> Overview of the Analysis </h2>
I have been tasked by stakeholders to see if there was any bias made by shoppers from reading Amazon Vine reviews prior to making their purchase(s). To do this, I took a dataset of digital music purchases and performed an ETL process for my analysis; where I extracted the data using Pyspark, transformed it to find certain data points, connected to an AWS RDS instance, then loaded the transformed data into pgAdmin.

<h2>Results </h2>
While going through my analysis, I wanted to address 3 questions:

<h4>How many Vine reviews and non-Vine reviews were there?</h4>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/VineReviews.png">
</p>
 
<h4>How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?</h4>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/ReviewCount.png">
</p>

<h4>What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?</h4>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/ReviewPercent.png">
</p>


<h2>Summary</h2>
The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
