## Weekend Challenge 1 : Takeaway Challenge


## Nouns
* restaurant
* customer
* menu 
* dishes / Prices
* text message

## Verbs
* order
* view menu
* add to menu
* sum total 


## Diagram Modelling

------------- | -------------
Class Name | Restaurant
Variables | Name = String
Methods  | select_available_dish()
Methods  | view_food_list()
Methods  | sum_order()

------------- | -------------
 Class Name | Menu
Variables  | {dishes => prices}
Methods  | show()
Methods | sum_dish_price()

------------- | -------------
 Class Name | Customer
Variables  | ......
Methods  | sum_order()
Methods | receive_confirmation_text()