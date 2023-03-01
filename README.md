# Object Relationships in RUBY
This repository focuses on object relationships and classes, their attributes and behaviours.

This repo contains Many to Many class relationship which is also called the Has-Many-Through relationship, which exists between two objects and occurs when a single instance of an entity, relates to many instance of another entity and vise versa. As an example we have three models: User, Review, and Product.For our purposes, a Product has many Users, a User has many Products’ s, and a Review belongs to a User and to a Product.Product - User is a many-to-many relationship.

Here is an image of the database ERD:

![Database ERD image](assets/ERDDiagram1.png)

## Tools Used
This project was built with the following tools:

- [Ruby ~ v3.1.+](https://www.ruby-lang.org/en/)

## Topics Covered
The following are the concepts covered in this practice session

- Active Record Migrations
- Active Record Associations
- Class and Instance Methods
- Active Record QueryingProject Setup
- Documentation on the Ruby language can be found here: [Ruby Docs](https://docs.ruby-lang.org/en/3.1/)
- Documentation on the Active Record can be found here: [ActiveRecord Docs](https://guides.rubyonrails.org/active_record_basics.html)

## Pre-requisites
In order to use this repo you need to have the following installed:

- OS [either: Windows 10+, Linux or MacOS(running on x86 or arm architecture)]
- Ruby - 3.1.+

## Installation

To use this repo on your machine requires some simple steps

### Alternative One

- Open a terminal / command line interface on your computer
- Clone the repo by using the following:

        git clone https://github.com/Ayub-Ian/ph3-ar-product-review.git

- Be patient as it creates a copy on your local machine for you.
- Change directory to the repo folder:

        cd ph3-ar-product-review

- (Optional) Open it in ``Visual Studio Code``

        code .

- (Alternate Option) Open it in any editor of your choice.
- Hurray! You are one step closer to being as intelligent as Einstein.

### Alternative Two

- On the top right corner of this page there is a button labelled ``Fork``.
- Click on that button to fork the repo to your own account.
- Take on the process in ``Alternative One`` above.
- Remember to replace your username when cloning.

        git clone https://github.com/your-username-here/ph3-ar-product-review.git


# Running the application

Running the application is very straight forward. You can use the following steps to run the app.

- Install required dependencies using bundle

      bundle install

- Run the application on the terminal

      ruby bin/run

# Authors
This project was contributed to by:
- [Ayub Ian](https://github.com/Ayub-Ian/)

# License
The project is licensed under MIT.
