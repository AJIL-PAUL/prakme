# ParkMe

ParkMe is a project aiming to create a peer to peer parking space network to solve the issue of limited parking space in major cities.

## Background And Overview

A person to person parking app that connects users in an area that need parking, with the users in an area offering parking. App utilizes Google Maps API to allow searches in a set area. Owners of parking spaces set their own price and set restrictions on type of car and range of stay.

## Functionality And MVP

- [x] User authentication and validation. Users are both renters and sellers.
- [x] Creating a property . Sellers will be able to publish details about their properties and also be able to set restrictions pertaining to the usage
- [x] Search - utilizes Google Maps and integrates with our API for targeted search anywhere in the US.
- [x] Renters will be able to filter and select parking spaces through the search and rent parking spaces according to their needs.
- [x] The application will be seeded with data and deployed in heroku.

## Bonus Features

- [ ] Seller property authentication.
- [ ] Direction to sellers location though maps .
- [ ] Add boat spaces to type of property and allow renters to rent boat spaces for boats.

## Technologies

- [x] MERN Stack: (Mongo, Express.js, React, Node.js)
- [x] Google MAPS API

## Wireframes

![Design Documentation](https://raw.githubusercontent.com/nmhalloran/parking-sniffer/master/wireframes/Parking.png)

## Accomplished over the weekend

- [x] Completed MERN stack tutorial and created project repo.
- [x] Completed Front end authentication.
- [x] Researched on Google Maps API and discussed on various places to implement it in our project
- [x] Completed all design documentation
- [x] Created and tested implementation of Maps Javascript Api to a location in map.

## Group Members and Work Breakdown

Alfred Alejandrino, Maxim Grebennikov, Nick Halloran, Meenakshi Anand Narayan

## Day 1

- [x] Create backend for sellers
- [x] Create backend for properties
- [x] Implement google map implementation necessary for sellers and properties
- [x] Implement routes and controller actions necessary for sellers and properties.

## Day 2

- [x] Implement redux cycle for sellers
- [x] Implement redux cycle for properties
- [x] Create backend for search model
- [x] Complete the necessary styling needed for user auth and creating a seller property form .

## Day 3

- [x] Complete the redux cycle for the search model .
- [x] Integrate Google maps view with populated seller property.
- [x] Complete the styling and test for edge cases.

## Day 4

- [x] Create the backend for the renters .
- [x] Create profile view for users.
- [x] complete redux cycle for users and renters .
- [x] Add necessary styling .

## Day 5

- [x] Start seeding the data .
- [x] Test all the mvp's for any errors.
- [x] Dedicate the day for styling and other unfinished issues .

## Day 6

- [x] Add pictures to both sellers and renters crete form .
- [x] Allow them to upload pictures using AWS and paperclip.
- [x] Continue styling .

## Day 7

- [x] Test the application for errors and deploy the app to heroku
- [x] Complete the project README
