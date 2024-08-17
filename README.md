# British Airways Virtual Internship

## Overview

During this virtual internship, I completed two tasks aimed at helping British Airways (BA) improve its customer experience and operational efficiency.

## Task 1: Web Scraping for Company Insights

### Business Problem

British Airways wants to understand customer perceptions of their experience with the airline in order to enhance operational efficiency and improve customer satisfaction.

### Approach

I used the BeautifulSoup library to perform web scraping on the following website: [Airline Reviews - British Airways](https://www.airlinequality.com/airline-reviews/british-airways). From the website, I extracted customer reviews and service ratings for analysis.

### Findings

- **Key Topics:** A word cloud generated from customer reviews revealed that topics like "flight," "seat," "service," and "time" are frequently mentioned, indicating that passengers often discuss their in-flight experience and the quality of service provided by the staff.
- **Customer Sentiment:** A significant portion of the reviews (63.3%) reflected dissatisfaction with the flights.
- **Service Ratings:** Analysis of service ratings showed that customers rated "Value for Money" and "Food and Beverages" the lowest. Specific issues included:
  - **Food and Beverages:** Customers complained about long wait times for food service and a limited selection of options. Additionally, free catering often only included a bottle of water and a packet of crisps.
  - **Value for Money:** Customers were frustrated by lengthy refund processes, with some being forced to use vouchers that ultimately increased their expenses. Delays in flights were also a common issue.

### Recommendations

1. Enhance free catering by offering customers a choice between water and soda, and provide more substantial food options like pastries or bread.
2. Introduce an option for customers to pre-order food and drinks before the flight, allowing the airline to prepare orders more efficiently.
3. Provide valuable vouchers and train employees to ensure that customers are not pressured into using them.

## Task 2: Predicting Customer Buying Behavior

### Business Problem

British Airways wants to identify the factors that influence whether customers complete or cancel their booking process.

### Approach

I built a predictive model using XGBoost to identify the features that most influence the completion of a booking.

### Dataset

The dataset (`customer_booking.csv`) was already clean, with no duplicate or null values, allowing for immediate analysis.

### Findings

Out of 50,000 booking processes, only 7,474 were completed. The model highlighted two key features that significantly impact whether a booking is completed:

1. **Purchase Lead:** The number of days between the booking date and the travel date. Unfinished bookings had a higher average purchase lead than completed bookings.
2. **Length of Stay:** Similarly, bookings that were not completed had a longer average length of stay than those that were completed.

### Recommendations

1. Offer attractive discounts for customers who book more than 30 days in advance.
2. Provide customers with the option to reschedule their bookings, with a deadline of up to three days before the flight.
