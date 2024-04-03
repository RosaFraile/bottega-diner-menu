# Bottega Diner Menu

### Build out a Diner Menu in JavaScript

> The customer can choose have: breakfast/lunch/diner.
> Breakfast Menu has different items.
> Lunch and Diner Menus have the same items but different prices (at lunch, items cost 1 euro less than at diner).

1. The waiter greets the customers. He tells them that thay can chose one item from the Main Menu and two items from the Sides Menu (the second item from the Sides Menu is optional).
2. The waiter asks the customers what are they going to have: breakfast, lunch or diner. Depending on their selection, we will show them different items on the Main Menu and the Sides Menu.
3. We show the customer the Main Menu.
4. The customers choose an item.
5. We check that the item is on the menu. If it is not, we go back to step 3.
6. We show the customers the Sides Menu.
7. The customer choose an item.
8. We check that the item is on the menu. If it is not, we go back to step 6.
9. The waiter makes a comment based on their selection. Comment can either be a comparison of the two items, or random comment pulled from a comment vault. The waiter totals up the cost of the two items.
10. The waiter asks the customers if they want another item from the Sides Menu.
11. If the customers' answer is "no", we jump to step 13.
12. If the customers' answer is "yes", we repeat steps from 6 to 8.
13. The waiter makes a random comment from the comment vault and totals up the cost (it will be the cost of 2 items or the cost of 3 items, depending on the answer of the customers at step 10).
