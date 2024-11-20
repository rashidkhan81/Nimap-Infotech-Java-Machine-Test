# Spring Boot Category and Product Rest API

## Project Description
In this  project,  Spring Boot application i have built two crud operation one is for category and second is for product.
i have also made server-side pagination.

#### These mentioned are working very well
3) Relation between Category-Products should have one-to-many relation. (One category can have multiple products).
4) Machine test should have Server side pagination.
5) While fetching single product details the response should be populated with respective category details.

* Tech Stack 
- Java
- Spring Boot
- Spring datan jpa and Hibernate
- MySQL
  
#Build spring boot project as a maven
# Run - Run as spring boot app

#Tested in the postman
*** Category CRUD
- GET /api/categories?page=3: Get all categories with pagination.
- POST /api/categories: Create a new category.
- GET /api/categories/{id}: Get category by ID.
- PUT /api/categories/{id}: Update category by ID.
- DELETE /api/categories/{id}: Delete category by ID.

*** Product CRUD
- GET /api/products?page=3: Get all products with pagination.
- POST /api/products: Create a new product.
- GET /api/products/{id}: Get product by ID (includes category details).
- PUT /api/products/{id}: Update product by ID.
- DELETE /api/products/{id}: Delete product by ID.

  Finally i have successfully achieved the target...........
