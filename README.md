# FoodXAnalysis
## EDA Findings and Observations
### Inital Hypothesis
![Menu_Item_Order_Freq](https://github.com/andylam20/FoodXAnalysis/assets/105662876/bf9a6b9d-7c15-43ec-887c-534095641646)
From the graph, it's evident that each item in the dataset has a nearly equal distribution of orders. This suggests that if we were to make random guesses about what the person ordered, we would have approximately a 10% chance of guessing correctly.

### Most Common Items Order per Time
One initial intuition for which feature might be helpful is time. This is because each food item is usually craved more depending on the time. For example, a bowl of cereal is generally more eaten in the morning.

![Items_Ordered_per_Time](https://github.com/andylam20/FoodXAnalysis/assets/105662876/2eaf477d-9bce-485a-9418-266101669798)
Based on the graph, we can see that there are general trends in which foods are more likely to be bought throughout the day. We can see that Breaded Pork Tenderloin Sandwich, Cornbread Hush Puppies, and Fried Catfish are more likely to be bought from opening hours to hour 10 and continue to be popular till noon. Around noon, other items including those mentioned previously and new items such as Indiana Corn on the Cob and Indiana Pork Chilli tend to also be extremely popular item choices before falling off around hour 13. This is when other items such as Hoosier BBQ Pulled Pork Sandwich, Indiana Buffalo Chicken Tacos, and Ultimate Grilled Cheese Sandwich are highly purchased. 

Based on the observed trends, it would be a strategic move for the business to consider emphasizing other items that align with the prevailing customer preferences at specific times. This can be accomplished through various means, such as setting up eye-catching signage, promoting different featured items, and tailoring these promotions to correspond with different times of the day. This approach can be a powerful tool for increasing overall sales, particularly when coupled with the main entrees. This strategy not only enhances the overall dining experience but also capitalizes on the fluctuations in customer preferences, potentially leading to increased revenue and customer
satisfaction.

### Most Common Items Order per Grade Year
I looked into whether grade year matters for food preference.
![Year 1](https://github.com/andylam20/FoodXAnalysis/assets/105662876/ca986ea8-3e59-4142-a167-161d0cc7b88b)
![Year 2](https://github.com/andylam20/FoodXAnalysis/assets/105662876/c55bc12c-f74e-4694-8336-aae63e7ce687)
![Year 3](https://github.com/andylam20/FoodXAnalysis/assets/105662876/dc457a71-952e-4a28-8189-5db69f8edc8e)
![Year 4](https://github.com/andylam20/FoodXAnalysis/assets/105662876/2b8461c3-8bc6-4f2f-a9b1-a52f6e16b8e1)

From first impressions, we can see that Year 1 and Year 4 have less than 30 samples so we can't assume anything from their data, however, students in Year 2 and Year 3 have much more samples. We can see from their data that there are potential taste differences. For example, we see that the top food items for both groups do not overlap meaning meaning that there is a taste difference depending on the year. 

One implication of this data is that it is heavily skewed toward Year 2 and Year 3 students. Similarly, the data does not consider college students who are staying longer than four years such as students getting a master's or doctorate degree in which they have to take more than the usual four years in college. Lastly, this data does not consider customers who do not go to school but want to try the food.

### Most Common Items Order per Universities
I wanted to figure out if there was a preference for a certain food based on the university the student went to.
![Valparaiso University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/2e5fc1e6-fcb1-4307-afd6-dd4654bdf474)
![University of Notre Dame](https://github.com/andylam20/FoodXAnalysis/assets/105662876/449ae660-6008-4ad6-90b7-292f34dccf26)
![University of Evansville](https://github.com/andylam20/FoodXAnalysis/assets/105662876/59a38e86-314e-4eac-86cf-44e9eeb410c4)
![Purdue University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/1970e2ba-75f8-4624-8a50-aa95cc1be8e6)
![Indiana University Bloomington](https://github.com/andylam20/FoodXAnalysis/assets/105662876/aa0e2b7f-83c2-4ebd-9c00-abe720621595)
![Indiana State University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/97aae9a6-5257-4fe6-8a85-d4e0d1e763a9)
![DePauw University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/e63a0a68-ae70-4013-8859-5e0c1994d9d1)
![Butler University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/b7cbb8aa-b34e-4810-974e-fc4a7acb6baa)
![Ball State University](https://github.com/andylam20/FoodXAnalysis/assets/105662876/f20f484c-d552-4a13-999e-2a56f775c88d)

From the data, we can see that DePauw, IU Bloomington, Purdue, and Valparaiso all have lower than 30 responses. This means that we can't make a conclusion about these universities. With the other universities above 30 samples, we see that certain universities prefer certain foods over others. 

With this finding, the business should focus more on marketing the foods that certain universities prefer.

### Most Common Items Ordered by Major
![Mathematics](https://github.com/andylam20/FoodXAnalysis/assets/105662876/dcadb498-7719-4ac3-84e0-c48e8a87a1ad)
![Marketing](https://github.com/andylam20/FoodXAnalysis/assets/105662876/abbda605-07c6-44bd-b93a-eb269f933a89)
![International Business](https://github.com/andylam20/FoodXAnalysis/assets/105662876/99aa7cea-1cac-4bea-8c3a-7aa758530dab)
![Fine Arts](https://github.com/andylam20/FoodXAnalysis/assets/105662876/1cb788f4-8459-48ed-8e61-931339cafac7)
![Finance](https://github.com/andylam20/FoodXAnalysis/assets/105662876/549edf49-61a4-405d-a77d-da083a4e9861)
![Economics](https://github.com/andylam20/FoodXAnalysis/assets/105662876/903c1295-4b1c-41f9-b890-76229bdb2498)
![Civil Engineering](https://github.com/andylam20/FoodXAnalysis/assets/105662876/150c377d-5163-40b2-a152-8666143db28d)
![Chemistry](https://github.com/andylam20/FoodXAnalysis/assets/105662876/2b2feabb-81a0-453c-8948-9713660195c5)
![Business Administration](https://github.com/andylam20/FoodXAnalysis/assets/105662876/69da32bf-0854-4932-b652-089c98765667)
![Biology](https://github.com/andylam20/FoodXAnalysis/assets/105662876/1af589e3-37fd-43c4-8d16-b87a8902da26)
![Astronomy](https://github.com/andylam20/FoodXAnalysis/assets/105662876/190bed0e-4582-4e72-ad4f-b1552f429fc2)
![Anthropology](https://github.com/andylam20/FoodXAnalysis/assets/105662876/abdb394e-919c-424d-9e08-347fca55fb8b)
![Accounting](https://github.com/andylam20/FoodXAnalysis/assets/105662876/afd55904-c63d-42be-a2d4-886f6c283a81)
![Sociology](https://github.com/andylam20/FoodXAnalysis/assets/105662876/fef70303-ccd2-4a72-b612-530ba8ffcf35)
![Psychology](https://github.com/andylam20/FoodXAnalysis/assets/105662876/867df70f-4fb5-4adb-922c-3a4fb6f9284c)
![Political Science](https://github.com/andylam20/FoodXAnalysis/assets/105662876/9d481f04-9a3e-438e-8970-837145a59be9)
![Physics](https://github.com/andylam20/FoodXAnalysis/assets/105662876/453c7608-b33c-48b9-8257-d7332290b72b)
![Philosophy](https://github.com/andylam20/FoodXAnalysis/assets/105662876/48a1d694-3fbe-4b58-950b-57427a7aa3c3)
![Music](https://github.com/andylam20/FoodXAnalysis/assets/105662876/f094f840-5526-4674-83e8-013afd8109ab)
![Mechanical Engineering](https://github.com/andylam20/FoodXAnalysis/assets/105662876/6af69978-bf13-4056-a4cd-d4d2a7e8e69e)

From the data, we can see that International Business, Music, Mechanical Engineering, Philosophy, Fine Arts, and Civil Engineering all have lower than 30 responses. This means that we can't make a conclusion about these majors. With the other majors above 30 samples, we see that certain majors prefer certain foods over others.

## Data 
## Model
## Conclusion
