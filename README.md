Project Description: Designing a Database for Bytes of China Restaurant
Overview
Bytes of China, a new restaurant in Chinatown, needs a robust database schema to manage and display its menu on their website. As a data engineer, your task is to design and implement this database, ensuring it captures all necessary details and relationships. Additionally, you will populate the database with sample data and create queries to extract useful information.

Objectives
Create Tables and Primary Keys:

Design tables for storing restaurant details, menu categories, dishes, and customer reviews.
Assign primary keys to ensure each record can be uniquely identified.
Define Relationships and Foreign Keys:

Establish relationships between tables (one-to-one, one-to-many, many-to-many) to maintain data integrity.
Implement foreign keys to enforce these relationships.
Insert Sample Data:

Populate the database with sample data to simulate real-world entries.
Ensure the data inserted adheres to the designed schema.
Make Sample Queries:

Write SQL queries to retrieve specific information, such as restaurant details, highest ratings, and menu items sorted by various criteria.
Demonstrate the ability to extract complex information using aggregate functions and subqueries.
Detailed Steps
1. Create Tables and Primary Keys
Restaurant Table: Store basic details of the restaurant including name, address, and contact information.
Address Table: Separate table to store address details linked to the restaurant.
Category Table: Define menu categories such as Appetizers, Soups, Main Courses, etc.
Dish Table: Store information about individual dishes, including name, price, description, and spiciness indicator.
Review Table: Store customer reviews with ratings and comments.
2. Define Relationships and Foreign Keys
One-to-One Relationship: Example between restaurant and address tables.
One-to-Many Relationship: Example between category and dish tables where one category can have multiple dishes.
Many-to-Many Relationship: Example between category and dish tables requiring a cross-reference table to handle multiple categories per dish.
3. Insert Sample Data
Populate each table with example entries to test the schema and relationships.
Ensure all necessary fields are filled to simulate actual usage.
4. Make Sample Queries
Query Restaurant Details: Retrieve the restaurant's name, address, and phone number.
Best Rating Query: Find the highest rating the restaurant has received.
Menu Query: Display dish names, prices, and categories sorted by different criteria.
Spicy Dishes Query: Retrieve a list of dishes marked as spicy.
Multi-Category Dishes Query: Identify dishes that belong to multiple categories using aggregate functions and nested queries.# Building-an-Inventory-Database-with-PostgreSQL
