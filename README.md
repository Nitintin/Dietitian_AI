# Dietitian_AI
The Artificial Intelligence Dietician is a bot with artificial intelligence about human diets. It acts as a diet consultant similar to a real dietician. Dieticians are eduated with food nutrient values. A dietician consults a person based on his schedule, body type, height and weight. The system too asks the data mentioned from the user like how many hours the user works, his height, weight, age, etc. and processes it. It then calculates the nutrient value needed to satisfy user needs. Based on the rules defined, the system shows an appropriate diet to the users and asks for affirmation regarding the same. In case the user is not satisfied, an alternate diet is provided for satisfying users’ needs.

Methodology Used

For the proposed project, a series of steps were followed for the system to recommend a diet plan.

Step 1: Clean and prepare the data as per the requirements

Step 2: Input details from the user: Age (in years), Weight (in pounds), Height (in Feet and Inches) and daily exercise level.

Step 3: Calculate Basal Metabolic Rate (BMR) using the Harris-Benedict Equations:
		Men BMR= 88.362 + (13.397 * weight in kg) + (4.799 * height in cm) – (5.677 * age in years)
		Women BMR = 447.593 + (9.247 * weight in kg) + (3.099 * height in cm) – (4.330 * age in years) 

Step 4: Calculate the calorie intake using the following table:

Exercise level	Daily Calories Required (Kcal/day)
Little to no exercise	Daily kilocalories needed = BMR x 1.2
Light exercise (1–3 days per week)	Daily kilocalories needed = BMR x 1.375
Moderate exercise (3–5 days per week)	Daily kilocalories needed = BMR x 1.55
Heavy exercise (6–7 days per week)	Daily kilocalories needed = BMR x 1.725
Very heavy exercise (twice per day, extra heavy workouts)	Daily kilocalories needed = BMR x 1.9

Step 5: Then we use randint(0,6) function to select items from list

Step 6: Recommend a diet plan based on the above steps. If not interested, look for an alternative plan using the defined rules by clicking on submit.
