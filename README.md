# FoodAppProject

Url 

http://localhost:9097/addCustomer

Customers Request

{
	"customerName" : "Abhishek",
	"customerAddress" : "BTM",
	"customerBalance" : 2000,
	"foodStatus" : "Accepted",
	"customerCart" : {
			"dishes" : 
			[
				{
					"dishName" : "Sizzlers"
				}
			
			]
	},
	"order":{
		"orderName" : "order1"
	}
}


Restaurant

http://localhost:9097/restaurants/addRestaurant

{
	"restaurantName" : "StarsCafe",
	"restaurantRating" : 4,
	"restaurantDishesCollection" : [
		{
			"rtDishName" : "Coffee",
			"rtDishPrice" : 70
		}
		
		]
}




