Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans:- This means that each product belongs to one category, as indicated by the "category_id" in the "Product" table, which is a foreign key referencing the "id" in the "Product_Category" table.Conversely, each category can have multiple products associated with it.
This is a common way to organize products in a database, allowing for efficient categorization and retrieval of products based on their category.

How could you ensure that each product in the "Product" table has a valid category assigned to it?
Ans:- To ensure that each product in the "Product" table has a valid category assigned to it, you can enforce referential integrity through the use of foreign key constraints in the database schema.
In this case, the "category_id" column in the "Product" table is a foreign key that references the "id" column in the "Product_Category" table.
By setting up a foreign key constraint between these two columns, you can ensure that every value in the "category_id" column of the "Product" table must exist in the "id" column of the "Product_Category" table.
