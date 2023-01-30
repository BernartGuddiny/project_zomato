# Exploring Zomato Bangalore Restaurant
![pandas 1.5.2](https://img.shields.io/badge/pandas-1.5.2-blue)
![seaborn 0.12.1](https://img.shields.io/badge/seaborn-0.12.1-brightgreen)
![scikit-learn 1.1.3](https://img.shields.io/badge/scikit--learn-1.1.3-orange)

### **Introduction**
Zomato is one of the best online food delivery apps which gives the users the ratings and the reviews on restaurants all over india. Restaurants from all over the world can be found here in Bengaluru. From United States to Japan, Norway to Antarctica, you get all type of cuisines here. Delivery, Dine-out, Pubs, Bars, Drinks,Buffet, Desserts you name it and Bengaluru has it.

Bangalore(officially known as Bengaluru) is the capital and largest city of the Indian state of Karnataka.

Bangalore has a unique food culture. Restaurants from all over the world can be found here in Bengaluru, with various kind of cuisines. Some might even say that Bangalore is the best place for foodies. The food industry is always at a rise in Bangalore, with 12,000 plus restaurants currently active in the city, the number is still increasing. The growing number of restaurants and dishes in Bangalore is what attracts me to inspect the data to get some insights, some interesting facts and figures.

### **The designation of the columns in the datasets:**
- url - contains the url of the restaurant in the zomato website;
- address - contains the address of the restaurant in Bengaluru;
- name - contains the name of the restaurant;
- online_order - whether online ordering is available in the restaurant or not;
- book_table - table book option available or not;
- rate - contains the overall rating of the restaurant out of 5;
- votes - contains total number of rating for the restaurant as of the above mentioned date;
- phone - contains the phone number of the restaurant;
- location - contains the neighborhood in which the restaurant is located
- rest_type - restaurant type;
- dish_liked - dishes people liked in the restaurant;
- cuisines - food styles, separated by comma;
- approx_cost(for two people) - contains the approximate cost of meal for two people;
- reviews_list - list of tuples containing reviews for the restaurant, each tuple;
- menu_item - contains list of menus available in the restaurant;
- listed_in(type) - type of meal;
- listed_in(city) contains the neighborhood in which the restaurant is listed.

### **The main goals of this project:**
- To find random restaurants with a known average check by converting the average check into the current USD rate and the current EUR rate;
- To find the most popular restaurants;
- To find favorite dishes and what is their popularity;
- To find the number of restaurants at each location.