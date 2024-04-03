# Bottega Diner Menu

### Build out a Diner Menu in JavaScript

> The customer can choose have: breakfast/lunch/diner.
> Breakfast Menu has different items.
> Lunch and Diner Menus have the same items but different prices (at lunch, items cost 1 euro less than at diner).
> The customer can choose one item from the Main Menu and two items from the Sides Menu. The second item from the Sides Menu is optional.

1. We show the customer the Main Menu.
2. The customer choose an item.
3. We check that the item is on the menu. If it is not, we go back to step 1.
4. We show the customer the Sides Menu.
5. The customer choose an item.
6. We check that the item is on the menu. If it is not, we go back to step 4.
7. The waiter makes a comment based on their selection. Comment can either be a comparison of the two items, or random comment pulled from a comment vault. The waiter totals up the cost of the two items.
8. The waiter asks the customer if he wants another item from the Sides Menu.
9. If the customer's answer is "no", we jump to step 11.
10. If the customer's answer is "yes", we repeat steps from 4 to 6.
11. The waiter makes a random comment from the comment vault and totals up the cost (it will be the cost of 2 items or the cost of 3 items, depending on the answer of the customer at step 8).
