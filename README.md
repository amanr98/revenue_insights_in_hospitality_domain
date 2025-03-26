# revenue_insights_in_hospitality_domain
Exploring revenue insights and creating dashboards to support data-driven decision-making for AtliQ Grands, a chain of five-star hotels in India.

# Hospitality Domain Power BI Dashboard

## Project Overview
This Power BI project analyzes booking trends and performance metrics across multiple properties in the hospitality domain. The dashboard helps stakeholders track key performance indicators, identify booking trends, and evaluate hotel performance.

## Dataset Information
This project leverages data from four datasets:

### 1. dim_date.csv
Contains date-related information to support time-based analysis.
- **date:** Specific calendar date.
- **mmm yy:** Month and year.
- **week no:** Week number.
- **day_type:** Indicates whether the day is a weekday or weekend.

### 2. dim_hotels.csv
Contains details about properties.
- **property_id:** Unique identifier for each hotel.
- **property_name:** Name of the hotel.
- **category:** Hotel category (e.g., Luxury, Business).
- **city:** City where the hotel is located.

### 3. dim_room.csv
Contains room category details.
- **room_id:** Unique identifier for each room category.
- **room_class:** Type of room (e.g., Standard, Elite, Premium, Presidential).

### 4. fact_aggregated_bookings.csv
Contains aggregated booking data.
- **property_id:** Unique identifier for each hotel.
- **check_in_date:** Date of check-in.
- **room_category:** Room category booked.
- **successful_bookings:** Number of successful bookings.
- **capacity:** Total capacity of the rooms.

### 5. fact_bookings.csv
Contains detailed booking information.
- **booking_id:** Unique identifier for each booking.
- **property_id:** Unique identifier for the hotel.
- **booking_date:** Date the booking was made.
- **check_in_date:** Date of check-in.
- **checkout_date:** Date of check-out.
- **no_guests:** Number of guests in the booking.
- **room_category:** Category of room booked.
- **booking_platform:** Platform used for booking (e.g., direct online, logtrip, makeyourtrip).
- **ratings_given:** Ratings given by guests.
- **booking_status:** Status of the booking (e.g., Checked Out, Cancelled, No Show).
- **revenue_generated:** Total revenue generated from the booking.
- **revenue_realized:** Actual revenue realized.

## Key Metrics and DAX Measures
The dashboard employs several key metrics calculated using DAX (Data Analysis Expressions) to derive meaningful insights:

- **Revenue:** Total revenue realized.
- **Total Bookings:** Count of total bookings.
- **Total Capacity:** Sum of room capacities across all hotels.
- **Total Successful Bookings:** Sum of successful bookings.
- **Occupancy %:** Ratio of successful bookings to total room capacity.
- **Average Rating:** Average rating given by guests.
- **Total Cancelled Bookings:** Count of cancelled bookings.
- **Cancellation %:** Percentage of cancelled bookings out of total bookings.
- **Total Checked Out:** Count of successful "Checked Out" bookings.
- **No Show Rate %:** Percentage of "No Show" bookings.
- **Booking % by Platform:** Percentage contribution of each booking platform.
- **Booking % by Room Class:** Percentage contribution of each room class.
- **ADR (Average Daily Rate):** Revenue per room sold.
- **Realisation %:** Percentage of successful check-outs over total bookings.
- **RevPAR (Revenue Per Available Room):** Revenue generated per available room.
- **DBRN (Daily Booked Room Nights):** Average rooms booked per day.
- **DSRN (Daily Sellable Room Nights):** Average rooms ready to sell per day.
- **DURN (Daily Utilized Room Nights):** Average rooms successfully utilized per day.
- **Week-over-Week (WoW) Change %:** Measures weekly change in revenue, occupancy, ADR, RevPAR, realisation, and DSRN.

## Insights and Visualizations
The Power BI dashboard offers several insights:
- **Booking Trends:** Track bookings over time, across weekdays and weekends.
- **Revenue Analysis:** Compare revenue generated vs. revenue realized.
- **Occupancy Rates:** Understand hotel occupancy across properties and room types.
- **Cancellation Rates:** Identify booking platforms with the highest cancellation rates.
- **Guest Preferences:** Analyze trends in room category selections.

## Tools & Technologies
- Microsoft Power BI
- Data Cleaning and Modeling
- DAX (Data Analysis Expressions) for custom calculations
- Interactive Visualizations

## How to Use
1. Download the Power BI report.
2. Open the .pbix file in Power BI Desktop.
3. Explore the interactive visualizations and gain insights into hotel performance.

![Hospitality_Domain](https://github.com/user-attachments/assets/d138da8f-43d7-4a8e-ac58-bf49fc6fdbd6)



