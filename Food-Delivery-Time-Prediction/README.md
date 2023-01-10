# Food Delivery Time Prediction

Predicting the delivery time of your order is a challenging task for every food delivery service like Zomato and Swiggy.

One of the best strategies to predict the delivery time is by calculating the distance between the point of picking up the order and the point of delivering the order. And then predicting the delivery time based on how much time your delivery partners took to deliver orders in the past for the same distance.

Below are all the features in the dataset:

- `ID`: order ID number
- `Delivery_person_ID`: ID number of the delivery partner
- `Delivery_person_Age`: Age of the delivery partner
- `Delivery_person_Ratings`: ratings of the delivery partner based on past deliveries
- `Restaurant_latitude`: The latitude of the restaurant
- `Restaurant_longitude`: The longitude of the restaurant
- `Delivery_location_latitude`: The latitude of the delivery location
- `Delivery_location_longitude`: The longitude of the delivery location
- `Type_of_order`: The type of meal ordered by the customer
- `Type_of_vehicle`: The type of vehicle delivery partner rides
- `Time_taken(min)`: The time taken by the delivery partner to complete the order

You are required to predict the delivery time based on the distance covered by the delivery partner to deliver the order.
