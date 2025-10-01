## Berkeley – Machine Learning and Data Science

**Franz Martinez**

### Context:

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

### Objective:
You seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 

### Data:

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under 20), coffee houses, carry out & take away, bar, and more expensive restaurants (
20 - $50).

### Inspection:
The coupon data was cleaned from empty values and inconsistencies, and after that, we conducted three analyses.
1.	An analysis to understand the percentage of accepted coupons and the distribution by type of restaurant and temperature.
2.	An analysis for bar coupons to understand the percentage of accepted coupons and the distribution by bar attendance, people age, and some other driver’s characteristics (income, marital status, car passengers, etc.) 
3.	An analysis for expensive restaurant coupons to understand the percentage of accepted coupons and the distribution by income, education, and restaurant attendance. 

### Results:
The outcome from our analysis was:
1.	For the coupon data, we observed that coupon acceptance rate is an effective strategy for all the restaurants (40% acceptance rate), especially for cheap restaurants and carry out restaurants (70% acceptance rate). Also, the coupon acceptance rate is higher on hot days (80F days), going from 1176 observations on 30F (53% acceptance rate) to 3727 observations on 80F (60% acceptance rate).

2.	For bar coupon data, they are used by young people (less than 30 years) that go to the bar more than 1 time per month. They usually go when they are driving with friends or partners (no kids), and, in terms of their economy, they earn less than 50K and they go to eat at cheap restaurants between 4 and 8 times per month.

3.	Expensive restaurant coupons will be more likely accepted by drivers earning more than 100k with a bachelor’s degree when they go more than 1 time per month to an expensive restaurant. Additionally, we observed that drivers earning more than 100K with Associate degree do not eat often in expensive restaurants (17 observances) compared to any other driver group earning more than 100K (some college, bachelor, graduate degree).
