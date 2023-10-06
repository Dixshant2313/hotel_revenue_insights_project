# Hotel Revenue Insights Dashboard README

## Introduction

This README file provides an overview of the dataset containing information about hotel bookings. The dataset is divided into five CSV files, each containing specific data related to hotels, rooms, and bookings. Additionally, a comprehensive Revenue Insights Dashboard has been created using Power BI, analyzing key metrics and providing valuable insights on the hotel data.

## Files Description

### 1. dim_date.csv

- **date:** Dates present in May, June, and July.
- **mmm yy:** Date in the format of month name and year (mmm yy).
- **week no:** Unique week number for each date.
- **day_type:** Indicates whether the day is a Weekend or Weekday.

### 2. dim_hotels.csv

- **property_id:** Unique ID for each hotel.
- **property_name:** Name of the hotel.
- **category:** Classifies the hotel as Luxury or Business.
- **city:** Location where the hotel is situated.

### 3. dim_rooms.csv

- **room_id:** Type of room (RT1, RT2, RT3, RT4) in a hotel.
- **room_class:** Classifies the room as Standard, Elite, Premium, or Presidential.

### 4. fact_aggregated_bookings.csv

- **property_id:** Unique ID for each hotel.
- **check_in_date:** Dates when customers checked in.
- **room_category:** Type of room (RT1, RT2, RT3, RT4) in a hotel.
- **successful_bookings:** Number of successful room bookings for a particular room type on a specific date.
- **capacity:** Maximum count of rooms available for a particular room type on a specific date.

### 5. fact_bookings.csv

- **booking_id:** Unique Booking ID for each customer.
- **property_id:** Unique ID for each hotel.
- **booking_date:** Date when the customer booked their rooms.
- **check_in_date:** Date when the customer checked in at the hotel.
- **check_out_date:** Date when the customer checked out of the hotel.
- **no_guests:** Number of guests who stayed in a particular room.
- **room_category:** Type of room (RT1, RT2, RT3, RT4) in a hotel.
- **booking_platform:** Method used by the customer to book the room.
- **ratings_given:** Ratings given by the customer for hotel services.
- **booking_status:** Indicates whether the booking was Cancelled, Checked Out, or No show.
- **revenue_generated:** Amount of money generated by the hotel from a particular customer.
- **revenue_realized:** Final amount received by the hotel based on booking status. If cancelled, 40% of the revenue generated is deducted.

## Revenue Insights Dashboard (Power BI)

A Revenue Insights Dashboard has been created using Power BI to provide detailed analysis and insights into key metrics related to hotel bookings. The dashboard includes visualizations and reports that highlight revenue trends, booking patterns, customer behavior, and other significant factors impacting the hotel business.

### Dashboard Highlights:

- **Revenue Trends:** Visual representation of revenue generated over the specified period.
- **Booking Patterns:** Analysis of peak booking times, popular room types, and booking platforms.
- **Customer Behavior:** Insights into customer preferences, ratings, and booking statuses.
- **City-wise Performance:** Comparison of revenue and booking metrics across different cities.
- **Room-wise Analysis:** Detailed breakdown of revenue, occupancy, and customer feedback for each room type.
- **Cancellation Analysis:** Understanding the impact of cancellations on overall revenue.

## Data Usage

This dataset, along with the Revenue Insights Dashboard, provides a comprehensive understanding of hotel booking data. Analysts and stakeholders can utilize this information to make data-driven decisions, optimize pricing strategies, and enhance customer satisfaction.

## Notes

- The dataset covers the months of May, June, and July.
- Please refer to individual column descriptions for specific details about each dataset.

For any additional questions or inquiries, please contact dixshantcharan2313@gmail.com.
