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

## Findings and Recommendations

### Findings (summary)

- Short travel distance is very important. When the place is close, people accept the coupon more.
- Coffee coupons are accepted more during the day, especially late morning and afternoon.
- People accept coupons more when they are with friends. When they have kids, acceptance is lower.
- Carry-out and cheap restaurant coupons are accepted more often than bar coupons or expensive restaurants.

### Actionable recommendations

- Focus on coupons that are close to the customer (around 5–15 minutes travel).
- Show coffee coupons mostly during daytime hours. Bar coupons work better in social or event times.
- Target users who are with friends or in social situations. Avoid strong targeting to drivers with kids.
- Keep redemption simple, especially for carry-out and low-cost restaurant coupons.

---

## Project Files

- **Jupyter Notebook**:  
  [prompt.ipynb](./prompt.ipynb)

- **Dataset Used**:  
  [data/coupons.csv](./data/coupons.csv)

- **Dependencies**:
  [requirements.txt](./requirements.txt)

