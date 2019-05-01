# WILDLIFE TRACKER-Trace Park

This is a java application used to track wildlife sightings in an area.

#### By **Marvin Zachary**

## Description

The application allows rangers to track wildlife sightings in an area. The user can add an animal to the system and report its sighting by providing details such as location, health and age. The animals added can either be endangered or not endangered. 

## Setup/Installation Requirements
    1. Clone the repository.
    2. Navigate to the file.
    3. Open with the text editor of your choice
    4.  Run "gradle run" to open the application on your browser.

#### To re-create the database, follow these steps;
In PSQL:
    1. CREATE DATABASE wildlife_tracker;
    2. \c wildlife_tracker;
    3. CREATE TABLE animals (id serial PRIMARY KEY, name varchar);
    4. CREATE TABLE endangered_animals (id serial PRIMARY KEY, name varchar, health varchar, age varchar);
    5. CREATE TABLE sightings (id serial PRIMARY KEY, animal_id int, location varchar, ranger_name varchar);
    6. CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;

## Behaviour driven Development (BDD)
|#User inputs | #Example outputs | 
|---------------|-------------------|
|When it receives: | It should return: |
| User adds an animal | An animal is added |
| User adds an endangered animal | An endangered animal is added |
| User reports an animal sighting | Animal sighting is reported |

## Technologies and language used
This application was written using Java programming language.

    1. Java development kit (Java SDK) - for creating the application
    2. Java Runtime Environment (JRE) - for executing the application
    3. Spark - web framework.
    4. Postgres SQL - Database

## Support and contact details
    • In case of any questions or feedback or clarifications, you can reach me at: acerzach@gmail.com

### License
    • Licensed under the MIT License
Copyright (c) 2019 **Marvin Zachary**
