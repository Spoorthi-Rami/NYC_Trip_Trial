# NYC_Trip_Duration
🚕 NYC Trip Duration Prediction

This project explores and analyzes the NYC Taxi Trip Duration dataset with the goal of predicting the trip duration using regression models. Ride-hailing services like Uber and Lyft rely heavily on accurate trip time predictions to optimize their dispatch systems and improve customer satisfaction. This assignment serves as an introduction to exploratory data analysis (EDA) and regression modeling for real-world transportation data.

🎯 Objective

To build and evaluate regression models that can predict the trip duration for NYC taxi rides based on geolocation, timestamps, and trip metadata.

📦 Dataset

You can download the dataset from the official Kaggle competition page (or a provided link, if available).

📑 Feature Descriptions
id: Unique identifier for each trip
vendor_id: Code indicating the provider (1 or 2)
pickup_datetime: Timestamp when the meter was engaged
dropoff_datetime: Timestamp when the meter was disengaged
passenger_count: Number of passengers (entered by driver)
pickup_longitude / pickup_latitude: Pickup location coordinates
dropoff_longitude / dropoff_latitude: Drop-off location coordinates
store_and_fwd_flag: Flag for delayed data transmission (Y or N)
trip_duration: ⏱️ Target variable (in seconds)
