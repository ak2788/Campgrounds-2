# Unit 5 Lab: Campground Explorer Part 2: Offline mode
## Overview
We previously created the Campground Explorer App! All was working great... until you turn on Airplane mode and reopen the app. When a user doesn't have service, (which happens often in parks!), we usually want to maintain some functionality. Storing some data locally in this way is called "caching", and to do it, we're going to use a local database.

## 🎯 Goals
- [x] Create a local SQLite Database with the Room Library
- [x] Define DAOs and Entities to interact with your database
- [x] Load cached local data in our RecyclerView when fresh network data is unavailable

## Application Features
The core requirements for this project are similar to Unit 4, but this unit we will allow a user to see a list of campgrounds, with the campground name, description, location, and image photo while offline.
- [x] Most recently fetched data is stored locally in a database
- [x] If user turns on airplane mode and closes and reopens app, old data from the database should be loaded

## App Walkthrough
Here's a walkthrough of implemented user stories:

<img src='https://github.com/user-attachments/assets/6b8b6e56-ea26-46bd-9443-c2fb22bfbce1' title='Video Walkthrough' width='30%' height='auto' alt='Video Walkthrough' />

GIF created with Canvas
