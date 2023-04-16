# python-api-challenge

## WeatherPy
This project utilizes the OpenWeatherMap API & Geoapify API to visualize the weather of over 500 cities in the northern and southern hemispheres. This challenge is broken down into two parts. 

1. WeatherPy
Create a series of scatter plots to show the relationship between weather variables and latitude. 
 
 * Latitude vs. Humidity
   - ![image](https://user-images.githubusercontent.com/124847109/232261805-2c9df32d-bee6-41a9-833a-6e66252347e5.png)

 * Latitude vs. Cloudiness
   - ![image](https://user-images.githubusercontent.com/124847109/232261833-d70f8beb-43a3-4ad6-96ef-3218dbac7c2c.png)

 * Latitude vs. Wind Speed
   - ![image](https://user-images.githubusercontent.com/124847109/232261844-ca2d4bfc-71a5-4a75-af44-aceaafe872aa.png)

 Computes and shows linear regression for each relationship
 
  * Temperature vs. Latitude Linear Regression Plot (Northern and Southern Hemisphere)
    - ![image](https://user-images.githubusercontent.com/124847109/232261869-67538c33-449e-4d87-8616-a493c6833ef7.png)
    - ![image](https://user-images.githubusercontent.com/124847109/232261882-94dc7183-b06e-4eb6-b3ad-bae81471e08d.png)
 
  * Humidity vs. Latitude Linear Regression Plot (Northern and Southern Hemisphere)
    - ![image](https://user-images.githubusercontent.com/124847109/232261892-ee92a56d-1a46-48a2-9eb1-2d4d973ea9e5.png)
    - ![image](https://user-images.githubusercontent.com/124847109/232261899-bc814738-7ee1-4267-a4c7-e0593a6a3131.png)

  * Cloudiness vs. Latitude Linear Regression Plot (Northern and Southern Hemisphere)
    - ![image](https://user-images.githubusercontent.com/124847109/232261923-b5a50d23-ea45-4005-9144-de4444f0633d.png)
    - ![image](https://user-images.githubusercontent.com/124847109/232261930-a53a6d68-250c-4d3d-90b7-313343fd08a5.png)

  * Wind Speed vs. Latitude Linear Regression Plot (Northern and Southern Hemisphere)
    - ![image](https://user-images.githubusercontent.com/124847109/232261942-dc8efbac-bfd3-4b1c-8b2d-3ec1b7b8cae3.png)
    - ![image](https://user-images.githubusercontent.com/124847109/232261948-a0f2da15-33b3-4427-bc56-4608f2b8e5f1.png)


2. VacationPy
Used geoviews and the Geoapify API to create a map that displays a point for every city using the size of point to show humidity. 
<img width="1133" alt="Screenshot 2023-04-15 at 8 58 21 PM" src="https://user-images.githubusercontent.com/124847109/232262088-381c1df8-4114-47d4-8d4f-35f4ccabe097.png">

Create a DataFrame that finds our ideal weather conditions, including, max temperature and cloudiness. 
<img width="737" alt="Screenshot 2023-04-15 at 8 59 46 PM" src="https://user-images.githubusercontent.com/124847109/232262116-5975764f-6f83-4539-bd2a-57b31836df78.png">


Find the first hotel located within 10,000 meters.
<img width="516" alt="Screenshot 2023-04-15 at 9 00 21 PM" src="https://user-images.githubusercontent.com/124847109/232262128-760c100e-4aab-409f-bfa2-53756e0d4bb5.png">

Add the hotel name and the country as additional information in the hover message for each city on the map. 
<img width="1023" alt="Screenshot 2023-04-15 at 9 01 00 PM" src="https://user-images.githubusercontent.com/124847109/232262160-5c44fd7c-a6d9-45cb-b1af-acb24936371e.png">
