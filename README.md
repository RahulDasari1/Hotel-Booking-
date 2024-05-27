# Hotel Booking Cancellation Analysis

![image](https://github.com/RahulDasari1/Hotel-Booking-Cancellation-Analysis/assets/101777162/d1f38953-fd55-4dcb-b928-971c777e722b)
_________________________________________________________________________________________________________________________________
![image](https://github.com/RahulDasari1/Hotel-Booking-Cancellation-Analysis/assets/101777162/1f762f05-d33b-4a2f-9893-2f8aecdd3583)
_________________________________________________________________________________________________________________________________
![image](https://github.com/RahulDasari1/Hotel-Booking-/assets/101777162/cae1cc8b-2d1c-4274-941a-2248d6718853)


## Project Overview
This project aims to analyze hotel booking cancellation patterns using the "Hotel Booking Demand" dataset available on Kaggle. The dataset contains detailed information on bookings for a City Hotel and a Resort Hotel between July 1, 2015, and August 31, 2017. The analysis will help identify key factors influencing booking cancellations and provide insights that could assist in improving booking strategies and customer retention.

## Dataset
The dataset consists of 119,390 observations, with each observation representing a hotel booking. The data has been anonymized by removing specific identifiers related to hotel and customer details. Four columns (`name`, `email`, `phone number`, and `credit_card`) were artificially added and are not used in the analysis.

### Key Columns in the Dataset
- `hotel`: Type of hotel (City Hotel or Resort Hotel)
- `is_canceled`: Indicates if the booking was canceled (1) or not (0)
- `lead_time`: Number of days between booking date and arrival date
- `arrival_date_year`, `arrival_date_month`, `arrival_date_week_number`, `arrival_date_day_of_month`: Details of the arrival date
- `stays_in_weekend_nights`, `stays_in_week_nights`: Number of weekend and weeknights the guest stayed or booked to stay
- `adults`, `children`, `babies`: Number of adults, children, and babies
- `meal`: Type of meal booked
- `country`: Country of origin of the guest
- `market_segment`: Market segment designation
- `distribution_channel`: Booking distribution channel
- `is_repeated_guest`: Indicates if the booking was from a repeated guest
- `previous_cancellations`: Number of previous cancellations by the customer
- `previous_bookings_not_canceled`: Number of previous non-canceled bookings by the customer
- `reserved_room_type`, `assigned_room_type`: Codes for reserved and assigned room types
- `booking_changes`: Number of changes/amendments made to the booking
- `deposit_type`: Type of deposit made
- `agent`, `company`: ID of the travel agent and company
- `days_in_waiting_list`: Number of days the booking was in the waiting list
- `customer_type`: Type of booking (e.g., Contract, Group, Transient)
- `adr`: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights
- `required_car_parking_spaces`: Number of car parking spaces required by the customer
- `total_of_special_requests`: Total number of special requests made by the customer

## Project Structure
The project is structured as follows:

1. **Data Loading and Cleaning**
    - Importing the dataset
    - Handling missing values
    - Removing or repurposing the artificially added columns

2. **Exploratory Data Analysis (EDA)**
    - Summary statistics of key features
    - Visualizing distribution of bookings and cancellations
    - Analyzing patterns based on hotel type, customer demographics, booking lead time, etc.

3. **Feature Engineering**
    - Creating new features from existing ones to better capture booking and cancellation patterns
    - Encoding categorical variables

4. **Model Building**
    - Selecting and training various machine learning models to predict booking cancellations
    - Evaluating model performance using appropriate metrics

5. **Results and Insights**
    - Interpreting the model results
    - Identifying key factors that contribute to booking cancellations
    - Providing actionable insights for hotel management

6. **Conclusion**
    - Summarizing findings
    - Discussing potential improvements and future work

## How to Run the Project
1. **Prerequisites**
    - Python 3.x
    - Jupyter Notebook or any compatible IDE
    - Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

2. **Setup**
    - Clone the project repository
    - Install required libraries using `pip install -r requirements.txt`
    - Download the dataset from [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand) and place it in the project's data directory

3. **Execution**
    - Open the Jupyter Notebook and run the cells sequentially
    - Follow the comments and instructions in the notebook to understand each step

## Acknowledgements
The dataset used in this project is from the article "Hotel Booking Demand Datasets," authored by Nuno Antonio, Ana Almeida, and Luis Nunes, and published in Data in Brief, Volume 22, February 2019.

## Inspiration
This analysis seeks to provide meaningful insights into the factors influencing hotel booking cancellations. By sharing this project, we hope to contribute to the broader data science community and inspire further research and innovation in the hospitality industry.

-Happy Coding <br>
Rahul Dasari
