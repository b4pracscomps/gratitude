# Gratitude Journal
Our Project, dedicated to our Professor, Ashok Patade

## Setup

* clone repo
* cd into directory
* `$ npm install`
* `$ npm start`
* `$ cd public`
* `$ gulp watch`  - this is important if you are making changes to the files in the   public folder


## Technologies and Libraries
### Front-End

* jQuery
* JavaScript
* HTML
* Sass/SCSS

### Back-End

* Node.js
* Express.js
* MongoDB
* Mongoose
* Mocha & Chai
* Gulp

### Version Control, Deployment and Continuous Integration

* GithHub
* Heroku
* mLab
* Travis CI

### Others

* Moment.js
* SweetAlert
* FontAwesome
* Flaticon



## RESTful API


### `/entries`  endpoint

#### GET
##### `/searchByUser/:userId`
returns all journal entries for a user

#### GET
##### `/:entryId`
returns the requested journal entry

#### POST
creates a new journal entry

#### DELETE
##### `/delete/:entryId`
deletes the requested journal entry for a user

#### DELETE
##### `/deleteAll`
deletes entries from all users/entire entry collection

#### PUT
##### `/:entryId`
updates requested entry



### `/user`  endpoint

#### GET
returns all registered users

#### GET
##### `/:username`
returns requested user

#### DELETE
##### `/:username`
deletes requested user

#### DELETE
##### `/deleteAll`
deletes all users/entire collection

#### PUT
##### `/:username`
updates requested user data



### `/auth`  endpoint

#### POST
##### `/register`
creates new user account

#### POST
##### `/login`
user authentication on login
