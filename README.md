# UMDB


User Movie Database (UMDB)

Project Description
UMDB is a platform where users can search for movies and see details about them. In addition, a user
can save their favorite movies, the watched movies and the to be watched ones.
Project Features
 Each user can create and login to their account
 A user can add/remove/see movies in his/her favorite/watched/to-watch lists
 A user can search for movies and see the details of any movie
 Extra:
o Users can search for each other
o Users can see other users lists
o Users can put their account to be private (no one can see them)

Features Details
 User:
o User is an entity that has the following information:
 Email
 Password
 Phone Number
 Country
 Gender
 Date of Birth
o Email and phone numbers are unique
o Email and Password are used to login
o Password must be hashed (encrypted in the DB)
 Move:
o Movie is the other entity in the project, a user can see the following information about a
movie:
 Title
 Year of release
 IMDB rating
 Main Picture
 Genre
 Plot
 IMDB link

Project Requirements:

 Django Backend
 Angular Frontend
 SQL based DB
 Movies are not stored in the DB but fetched from IMDB database. We cannot save all the moves
in our DB, however when a user search for a specific name, we have to use IMDB API to get all
the information needed about the movie and display them to the user. When a user adds a
movie to a list, it is sufficient to add only the IMDB id of such movie in corresponding table in the
DB.
 Use sessions and middleware properly
 Use caching to store movies information instead of calling IMDB API every time.

Learning Objectives:
 Setting Up backend and frontend environment
 Password Hashing
 Use of third-party API
 Use of Caching, Sessions and Middleware