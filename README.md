# Hotel_Booking_Analysis-Capstone-Project

## Objective
We are provided with a hotel bookings dataset for EDA.

Out main objective is to perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

Hotel bookings depend on many factors such as type of hotels, seasonality, days of week, meals available, parking spaces, charges etc. Hence analysing the patterns available in the past data is very important to help the hotels plan well accordingly in order to benefit the business. The given data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, the number of adults, children, and/or babies, and the number of available parking spaces etc, we tried to understand the customer’s’ behaviour and useful patterns in the data to help hotel managements improve the business by taking better decisions. The sequence of processes carried out to analyse the data is mentioned below:

## Attribute information:
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

•	Total number of rows in data: 119390

•	Total number of columns: 32

## Data Preparation:

Data preparation ensures accuracy in data, which leads to accurate insights. Without data preparation, it’s Possible that insights will be off due to junk data. i.e. No quality data, no quality mining results!

It includes basic inspection on the raw data, Data Cleaning by handling missing values. We also treated outliers first by capping method, we defined some thresholds to cap some of the categorical features, then we handled the outliers in remaining features by standard IQR method, after that we did some feature engineering in order to understand the patterns in latent features.

## Exploratory Data Analysis:

We performed univariate, Hotel Wise comparison, bivariate, multivariate and correlation analysis by plotting some visualizations and data wrangling to find out useful insights and make overall inferences to reach to a conclusion.

We encountered following patterns in the given historical data:

- Top Hotel - City Hotel. Top Agent - Agent No. 9. Top room type - A
- One out of every three bookings are cancelled.
- People prefer to tour more in August.
- Most preferred meal is BB (Bread and Breakfast.
- Online marketing is the best way to attract customers.
- People do not want to pre-deposit the money for booking.
- Only 10% of people require parking space.
- Most of the visitors are couples.
- The Resort hotel is preferred mostly for longer stays, day time stays. and when the parking space is needed.
- More than 15 days advance bookings have high chances of cancellation.
- Assigning a different room is not a reason for cancellation.
- Direct bookings have very less cancellation%.
- Best time to book a hotel is in January.
- Average days in advance booking: 77 days.
- Average nights spent by visitors: 3.
- Most visitors are from Portugal, Britain, France, Spain and Germany.
- Total Special requests and the revenue depends more on total members arrived.

In this project, we also analysed the factors affecting the hotel bookings which may be useful to predict the future bookings, cancellations and number of special requests.





