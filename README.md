# Summary
A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

# Data Dictionary
| Table      | Field         | Description                                     |
|------------|---------------|-------------------------------------------------|
| orders     | order\_id     | Unique identifier for each order                |
| orders     | date          | Date the order was placed                       |
| orders     | time          | Time the order was placed                       |
| order\_det | order\_det\_id | Unique identifier for each order detail record |
| order\_det | order\_id     | Foreign key referencing the orders table       |
| order\_det | pizza\_id     | Foreign key referencing the pizzas table       |
| order\_det | quantity      | Quantity of the pizza in the order detail      |
| pizzas     | pizza\_id     | Unique identifier for each pizza                |
| pizzas     | pizza\_type\_id | Foreign key referencing the pizza\_types table   |
| pizzas     | size          | Size of the pizza                               |
| pizzas     | price         | Price of the pizza                              |
| pizza\_type | pizza\_type\_id | Unique identifier for each pizza type          |
| pizza\_type | name          | Name of the pizza type                          |
| pizza\_type | category      | Category of the pizza type                      |
| pizza\_type | ingredients   | Comma-separated list of ingredients            |
