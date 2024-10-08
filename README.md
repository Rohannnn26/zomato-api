# Zomato EDA

1.The dataset is highly skewed toward the cities included in Delhi-NCR. So, we will summarise all the other cities in Rest of India while those in New Delhi, Ghaziabad, Noida, Gurgaon, Faridabad to Delhi-NCR. Doing this would make our analysis turn toward Delhi-NCR v Rest of India.

	a.Plot the bar graph of number of restaurants present in Delhi NCR vs Rest of India.

	b.Find the cuisines which are not present in restaurant of Delhi NCR but present in rest of India.Check using Zomato API whether this cuisines are actually not served in restaurants of Delhi-NCR or just it due to incomplete dataset.

	c.Find the top 10 cuisines served by maximum number of restaurants in Delhi NCR and rest of India.

	d.Write a short detailed analysis of how cuisine served is different from Delhi NCR to Rest of India. Plot the suitable graph to explain your inference.


2.User Rating of a restaurant plays a crucial role in selecting a restaurant or ordering the food from the restaurant.

	a.Write a short detail analysis of how the rating is affected by restaurant due following features: Plot a suitable graph to explain your inference.

		a1.Number of Votes given Restaurant

		a2.Restaurant serving more number of cuisines.

		a3.Average Cost of Restaurant

		a4.Restaurant serving some specific cuisines.

	b.Find the weighted restaurant rating of each locality and find out the top 10 localities with more weighted restaurant rating?
	Weighted Restaurant Rating=Σ (number of votes * rating) / Σ (number of votes) .


3.Visualization

	a.Plot the bar graph top 15 restaurants have a maximum number of outlets.
	b.Plot the histogram of aggregate rating of restaurant( drop the unrated restaurant).
	c.Plot the bar graph top 10 restaurants in the data with the highest number of votes.
	d.Plot the pie graph of top 10 cuisines present in restaurants in the USA.
	e.Plot the bubble graph of a number of Restaurants present in the city of India and keeping the weighted restaurant rating of the city in a bubble.
