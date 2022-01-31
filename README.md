# Rate-E-Restro
This Project is build using HTML,CSS and Javascript for frontend and Node.js and it's frame works for backend.MongoDb is used as the Database. 

## There are 5 main pages:
* landing page: This page is the home page.
* Login page: This is the Login page.
* Sign Up page: This is the register/signup page.
* Index page: This is the page to show all the Restro Experiences in the database.
* Show page: This page shows details of a particular Experience from here you can add comment, edit Experience and delete a particular Experience.

**Authorization** is taken into account while giving rights to a user to edit or delete an Experience.Only the user who had made a particular Experience can delete or edit that Experience. 

**Authentication** is also taken into account while adding comments( a user can only add comments if he/she is logged in).




* Authentication:
  
  * User login with username and password

  * Admin sign-up with admin code

* Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

  * Admin can manage all posts and comments

* Manage campground posts with basic functionalities:

  * Create, edit and delete posts and comments

  * Upload Restaurant photos

  * Display Restaurant location on Google Maps
  
  * Search existing Restaurant

* Manage user account with basic functionalities:


  * Profile page setup with sign-up

* Flash messages responding to users' interaction with the app

* Responsive web design

### Custom Enhancements

* Update Restaurant photos when editing Restaurants

* Update personal information on profile page

* Improve image load time on the landing page using Cloudinary

* Use Helmet to strengthen security
 


## Built with

### Front-end

* [ejs](http://ejs.co/)
* [Google Maps APIs](https://developers.google.com/maps/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [async](http://caolan.github.io/async/)
* [crypto](https://nodejs.org/api/crypto.html#crypto_crypto)
* [helmet](https://helmetjs.github.io/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [nodemailer](https://nodemailer.com/about/)
* [moment](https://momentjs.com/)
* [cloudinary](https://cloudinary.com/)
* [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)
