

## Professional Certificate in Machine Learning and Artificial Intelligence.
---

### Practical Application Assignment 5.1
## Will a Customer Accept the Coupon?
### Data
This data comes to from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

### Deliverables
Your final product should be a brief report that highlights the differences between customers who did and did not accept the coupons. To explore the data you will utilize your knowledge of plotting, statistical summaries, and visualization using Python. You will publish your findings in a public facing github repository as your first portfolio piece.

A more detailed explanation for the attribute of the dataset located on the following link.

source : https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation

Note: The term "Customers", "Bar goers" and "Drivers" will be used to describe the demography of the data collected/described.




## Observations

After the data is cleaned up and processed these are some of the observations drawn.
+ The gender distribution of the data is almost equally distributed but there is a slight increase on Female drivers.
+ Female drivers tend to have a higher tendency to reject and less tendency to accept coupons compared to Males.
+ Of the offered coupons majority of the accepted are those with 1 day expiration date and the rejected ones have equal amount of coupons of one day and 2 hours of expiration.
+ Percentage/portion of total observation chose to accept the coupon is: 57.0%
+ The highest offered coupons are those for Coffee Houses and the lowest for expensive restaurants.
+ of the provided age groups, age group 21-25 have the highest groups the accept a coupon followed by age group 26-31, and drivers below the age of 21 have the lowest age group to accept a coupon offer.
+ 41.19% of the Bar coupons offered are accepted.
+ The highest rejection of Bar coupons came from customers who never visited the bar.
+ Customers who visited at least three times a month and once in a while are the group of customers who jointly accept than the others.
+ Customers who went to bar to 3 or less times a month have high percentage(~50%) of accepting a coupon to customers who went to the bar more frequently (7%), which is unexpected.
+ Drivers who frequent bars more than once a month and older are tend to accept the coupons (87.8%) more than those frequent less and younger than 25 years of age (60%).
+ Percentage of acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, & forestry make up 18.42% of the total.
+ Percentage of acceptance of drivers go to bars more than once a month, had passengers that were not a kid, and were not widowed : 32.35%
+ Percentage of acceptance go to bars more than once a month and are under the age of 30 : 19.83%
+ Percentage of acceptance of drivers go to cheap restaurants more than 4 times a month and income is less than 50K : 19.40%.
+ Majority of the coupons accepted are offered around 6PM and those rejected offered around 7AM.
+ Coffee house coupons are equally accepted and rejected and Restaurant under $20 and carryout/take away coupons are the highest accepted and Bar coupons are the highest rejected next to Coffee House coupons
+ Sunny days are the best days for to offer coupons.
Unemployed customers leads in numbers in accepting and rejecting coupons. With "Farming Fishing and Forestry" accept the least amount of coupons and "Building, group and Maintenance" occupation groups having the least rejection of coupons.

+ Single customers have the highest coupon acceptance rate followed by Married partners but Married partners have highest rejection followed by Singles.

---

For more, please open up the Jupyter note book with plots and markdowns in this repo.



## Thank you

