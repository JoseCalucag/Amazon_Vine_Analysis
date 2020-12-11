

<h1 align = "center"> Amazon_Vine_Analysis </h1>

<p align = "center">
<img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKZes_QAmSFjPJ1kwI6NEFYGHu_GW3qRRNeg&usqp=CAU"width = "600" height = "300">
 </p>

<h2> Overview of the Analysis </h2>
I have been tasked by stakeholders to see if there was any bias made by shoppers from reading Amazon Vine reviews prior to making their purchase(s). To do this, I took a dataset of digital music purchases and performed an ETL process for my analysis; where I extracted the data using Pyspark, transformed it to find certain data points, connected to an AWS RDS instance, then loaded the transformed data into pgAdmin.

<h2>Results </h2>
While going through my analysis, I wanted to address 3 questions:

<h3>How many Vine reviews and non-Vine reviews were there?</h3>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/VineReviews.png">
</p>
* Through our first analysis, we can already conclude that there was no bias when it comes to digital music pruchases as 1,688,881 reviews were made by non-Vine members.
 
<h3>How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?</h3>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/ReviewCount.png">
</p>
* As there were no Vine members, I put my focus on the non-Vine 5 star reviews. As we can see in the above visual, 1,345,146 were 5 star reviews, leaving 343,735 non-5 star reviews.


<h3>What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?</h3>
<p align = "left">
<img src = "https://github.com/JoseCalucag/Amazon_Vine_Analysis/blob/main/pics/ReviewPercent.png">
</p>
* As prior, I put my focus on the non-Vine 5 star review percentage, which was around 79.6%.

<h2>Summary</h2>
After reflecting on my results, it was easy to assume that customers wouldn't have any bias to their digital music purchases as people tend to not buy music based upon what other people say but based upon their own palette. To elaborate, when have you ever purchased music you've never heard of based on what someone said? The buyer probably had a pre-concieved idea of what the artist sounded like,maybe did a little research then went ahead and made the purchase; which is prolly why there's still a 20% of non-5 star reviews. If we were to take the analysis forward, I would probably want to see if any of the custmers were Amazon music members and see if those purchases fit in their music listening profiles. With that, you can see if there was any outside biases to consider (i.e. movie/tv show soundtracks, friend/network recommendations, etc.)
