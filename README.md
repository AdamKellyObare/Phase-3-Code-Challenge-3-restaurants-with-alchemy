# Phase-3-Code-Challenge-2
For this challenge, we are working with a Yelp-style domain.

We have three models:

*Restaurant
*Customer
*Review

For our purposes, a Restaurant has many Reviews, a Customer has many Reviews, and a Review belongs to a Customer and to a Restaurant.

Restaurant - Customer is a many-to-many relationship.

Topics covered:

Classes and Instances
Class and Instance Methods
Variable Scope
Object Relationships
lists and list Methods

# Migrations
Before working on the rest of the deliverables, you will need to create a migration for all tables.

 

- A `Review` belongs to a `Restaurant`, and a `Review` also belongs to a  `Customer`.  In your migration, create any columns your `reviews` table will

 need to establish these relationships.

The `reviews` table should also have:  - A `star_rating` column that stores an integer.
 

After creating the `reviews` table using a migration, use the `seeds.py` file to create instances of all your classes so you can test your code.

# Requirements
- A well and stable secured internet connection
- A properly functioning Laptop, Ipod, Tablet or phone

# Deliverables
-For this Project we were required to write the following methods in the classes. Feel free to build out any helper methods if needed.

-> NB:Remember: SQLAlchemy give your classes access to a lot of methods already! Keep in mind what methods SQLAlchemy gives you access to on each of your, classes when you're approaching the deliverables below.

# Language Used
* Python.


# Project Pipfile
For this project, we have a specified pipfile to download/copy and paste to our worksheet :
    [source]
    url = "https://pypi.org/simple"
    verify_ssl = true
    name = "pypi"

[packages]
alembic = "*"

[dev-packages]

[requires]
python_version = "3.10.7"

# Requirements
For this project we were required to use:
* Aggregate and Relationship methods
* Object Relationship Methods