### Answer to Question 2 in Quiz
Here I use the microburbs response api to get housing information.
I clean that housing information into a pandas dataframe with address and co-ordinates.
I then use these co-ordinates to find the nearest road, and nearest point on that road to the house.
Following this, I calculate the direction to that nearest point on the road and that is assumed to be the direction that the house is facing.

The code used to generate this is saved in 
[house_direction.ipynb
](https://github.com/GeraldFreis/ResponseForTest/blob/main/house_direction.ipynb)And the output generated is saved into 
[address_direction.csv
](https://github.com/GeraldFreis/ResponseForTest/blob/main/address_direction.csv)
