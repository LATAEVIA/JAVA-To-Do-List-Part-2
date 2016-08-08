# _JAVA To Do List Part 2_

#### _PRACTICE - accessing a Postgres database using Java applications by recreating [JAVA-To-Do-List-Part-1] (https://github.com/LATAEVIA/JAVA-To-Do-List-Part-1) using One-to-One REStful routing and a database to store tasks., 05/07/2016_

#### By _**LaTaevia**_

## Description

_Java application where users can add tasks to do list, and organize tasks by category. All data is stored in a server and can be viewed even after the application is refreshed or closed._

## Prerequisites

You will need the following properly installed on your computer.

* [Gradle](https://gradle.org/gradle-download/)
* PostgreSQL on Mac with HomeBrew `brew install postgres` 
* [PostgreSQL (All OS)] (http://www.enterprisedb.com/products-services-training/pgdownload#windows)

## Installation

* `git clone https://github.com/LATAEVIA/JAVA-To-Do-List-Part-2.git`
* Change into the new directory
* In a new terminal window/tab `postgres` to launch postgres
* In another new terminal window/tab `psql` to launch psql
* In psql window/tab `CREATE DATABASE best_restaurant;`
* In the terminal window/tab `psql best_restaurant < best_restaurant.sql`
* In psql window/tab `CREATE DATABASE to_do_test WITH TEMPLATE to_do;`
* `gradle build`

## Running / Development

* `gradle run`
* Visit app at [http://localhost:4567](http://localhost:4567).

## Technologies Used

* _HTML_
* _CSS_
* _Bootstrap_
* _Java_
* _Gradle_
* _Spark_
* _Velocity_
* _FluentLenium_
* _PostgreSQL_

### License

*This software is licensed under the MIT license*

Copyright (c) 2016 **_LaTaevia_**
