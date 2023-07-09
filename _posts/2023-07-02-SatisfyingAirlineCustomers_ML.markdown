---
layout: post
title:  "Satisfying Airline Customers"
tagline: Machine Learning for Business Recommendations
date: 2023-06-25
categories: [Machine Learning]
tags: [Travel, Airline, XGBoost]
image: img-air.jpeg
permalink: /airline-satisfaction.html
---

<strong> Problem Statement </strong>

The motivation of this project primarily focuses on how to improve customer Satisfaction. Customer Satisfaction relates to multiple dimensions, such as maximizing profit, keeping a loyalty program, and solving the common concerns of the airline field.

Customer Satisfaction directly links to our profit. Giving a warm flight experience will lead to a high customer satisfaction rate which can boost our brand reputation, causing more passengers to choose to fly with our airlines. Thus, when the airline spends the same amount to run the flight, the revenue from selling the flight ticket will increase, increasing our profit simultaneously.

Also, the loyalty program can be affected by customer satisfaction as well. A high customer satisfaction rate will allow the airline to compete domestically for its loyalty program. A good example is Delta Air Lines. Delta Air Lines has a high customer satisfaction rate compared to the other two significant US airlines, which enables the airline to hold 100 million members by 2020 and generate around $6.1 billion from selling miles.

Ultimately, customer satisfaction is a metric that the airline industry collectively wants to improve. Whoever can solve many common problems first will occupy the source of customers and ticket prices. For example, All Nippon Airways proposed changing the seat layout of Boeing 777-300 from the original 3-4-3 to 2-4-3 and using the middle as a partition to give passengers more large hand movement space. Due to this design, ANA's customer satisfaction has greatly improved. It has defeated United Airlines, a member of the Star Alliance with absolute quality in the round-trip route between Japan and the United States.

Our problem is to classify the flight experience by the predicted customer satisfaction in order to reduce the amount of customers that review their experience as ‘dissatisfied.’ The problem is a binary classification problem to determine ‘satisfied’ or ‘dissatisfied.’ Predicting flight satisfaction will provide data to help inform our service quality and retain customer loyalty, thus reducing customer dissatisfaction. The number of satisfied and dissatisfied customers per year can be compared to data from previous or future performance and against competitors to determine the level of success or failure of the project and significance of change. Metrics should be observed on monthly data; however, due to the seasonality of traveling and volatility of travel demands based on the economy, the performance of the model should be evaluated on at least a year's worth of data.

<strong> Conclusion </strong> 

Our team separated recommendations into customer satisfaction improvement and loyalty customer engagement. First, let's take a look at our customer satisfaction. Bases on our model analysis, we found that the features of in-flight entertainment and seat comfort most impacted our customer satisfaction. Thus, we decided to focus on enhancing the in-flight customer experience. Most airlines have partnerships with movies or TV show companies. For example, Delta Airlines has a tight relationship with HBO, and  United Airlines has a partnership with Disney Movies. We want our customers to have more movie or TV show choices during their flights. Thus, we recommended that our airlines collaborate with more entertainment companies. Besides the movie and TV shows, wifi service has also influenced our in-flight entertainment quality.

In-flight wifi is the only way to connect to the internet and receive information from others. Therefore, we suggest collaboration with in-flight wifi service providers to help them invent high-speed wifi service, providing our customers with an excellent experience. Also, we should spread our wifi service to accommodate not only large aircraft but also small domestic aircraft because many business travelers who need in-flight wifi service to handle work are flying domestically. Secondly, seat comfort impacts customer satisfaction significantly. We want to provide our seats with comfortable material, especially for long-distance economy-class flights. That will give our customers an excellent in-flight experience as well.

The loyalty program plays an essential role for our company as well. Even though there are many airline choices, customers prefer to stay at a specific airline and enjoy the airline's program benefits. Thus, we should launch a good loyalty program for our customers. For example, we increase miles transfer partners, let loyal customers enter the lounge to wait for their flight, and expand airline alliances, allowing our customers to book our partner flights using our miles. Depending on the statistical data, we also need to cooperate with our flight scheduling team to find the optimized departure time, allowing our customers to have a suitable flight schedule. In the future, further studies to understand how customer satisfaction increases loyalty due to the improved loyalty program benefits will help efficiency with budget use for benefits.

<pre><code>

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSPVdvnh6_n2m8Gqe796MWW5qKdA4gqBcwighbpVspyW28pkXfZvuAeB9IiIQffNQ2OWbdCwwotJb9q/embed?start=false&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

</code></pre>