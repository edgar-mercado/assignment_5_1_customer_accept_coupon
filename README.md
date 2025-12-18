# Coupon Acceptance Analysis

## Overview
In this project, I looked at customer data to understand what differences exist between people who **accepted** a coupon and those who **did not accept** it. The goal is to see what kind of situations or behaviors make a customer more likely to use a coupon.

---

## Main Observations

### Coupon Type
Some coupons were accepted more often than others.  
Coupons for **carry out & take away** and **cheap restaurants** had higher acceptance rates.  
Coupons for **bars** and **more expensive restaurants** were accepted less.

This suggests that people prefer coupons that are easy and low effort to use.

---

### Who the Customer Is With
Acceptance also changes based on who the customer is traveling with:
- Higher acceptance when the customer is with **friends**
- Slightly lower when with a **partner**
- Lower when the customer is **alone**
- Lowest when the customer is with **kids**

Coupons seem to work better in social situations and less when there are more responsibilities.

---

### Time of Day
Coupons were accepted more often during **midday**, such as late morning or afternoon.  
Early morning and late night show lower acceptance.

This could be because people are more relaxed and flexible during the day.

---

### Distance to the Place
Travel distance is one of the strongest factors:
- Short distances (around 5 minutes) have higher acceptance
- Acceptance decreases as travel time increases

If the place is too far, people are less likely to use the coupon.

---

### Habits (Bars and Coffee Shops)
Customers who go to bars or coffee shops **occasionally** tend to accept coupons more often.  
People who go **very frequently** or **never** show lower acceptance rates.

Coupons seem to be more effective for occasional visitors.

---

## Conclusion
Customers who accept coupons usually prefer:
- Convenient and easy offers  
- Short travel distances  
- Social situations  
- Flexible times of the day  

Customers who do not accept coupons are often in situations where the offer feels less convenient or less useful.

Overall, context and customer behavior play an important role in coupon acceptance.

---

## Project Files

- 📓 **Jupyter Notebook**:  
  [prompt.ipynb](./prompt.ipynb)

- 🌐 **HTML Export of the Analysis**:  
  [prompt.html](./prompt.html)

- 📊 **Dataset Used**:  
  [data/coupons.csv](./data/coupons.csv)

- 📦 **Dependencies**:
  [requirements.txt](./requirements.txt)

> Note: The HTML file is an exported version of the notebook for easy viewing without running code.
