# Kaffa Coffee

Welcome to [Kaffa Coffee](https://kaffa-coffee-1c360e949e52.herokuapp.com/), an Ethiopian coffee shop built as part of my e-commerce specialization project portfolio for the Full Stack Software Development diploma at Code Institute. This webshop is designed for coffee lovers, offering a taste of "the kingdom of Kaffa," the birthplace of coffee. Our webshop is straightforward, featuring a shop page, about page, and a signup page for users to receive newsletters and updates on new coffee arrivals. 
<img width="627" alt="homepage_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/d8e4dd40-8c27-437d-b5ca-c70f02e52cb9">
<br>(This is how I envision the landing page when the project is finished)

## Planning
At the beginning of this project, I considered the following questions to guide the development of the application:
<br>
<br>
**Who is the customer?** B2C - Business to Customer
<br>
**What will they buy?** Coffee products
<br>
**How will they pay?** Single payment
<br>
<br>
With these considerations, I planned the e-commerce application to include:
<br>
- **E-commerce application types: **
  <br> B2C, Products, Single payments
- **Features:**
  <br> Easy Payment, User Authentication, Social Media Authentication, Search Functionality, Product Descriptions, Ratings/Reviews, Contact Form, Shopping Cart, Payment System, and Wishlist
- **Database tables:**
  <br> User: username, email, password
  <br> Product: name, image, price, description, rating
  <br> Order: User, total, full_name, address
  <br> OrderItem: Order, Product, quantity
  <br> Wishlist: user, product

## Features
I have just started off with my project. Because of medical leave and parental leave I have lost some time and fallen behind.
But this is approximently the way I want it to look when the project is finished. All of the images comes from my wireframes and this is how I am imagin it to look like.
<br>
<br>
### Navigation bar
<img width="627" alt="navbar_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/8fac87df-08d4-4347-9a41-c1094715170a">
<br>(This is how I envision the navigation bar on desktop when the project is finished)
<br> Simple and easy to use.
<br>
<br>
<img width="288" alt="navbar_mobile" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/cc6aa6b3-a4cb-40b0-8a88-60c278326c05">
<br>(This is how I envision the navigation bar on smaller devices when the project is finished)

### Landing page
<img width="627" alt="homepage_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/35ba6d45-4745-4539-af0d-33d2a8f95c36">
<br>(This is how I envision the landing page when the project is finished)

### Bundles
<img width="627" alt="bundles" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/28826fcb-ac61-4d7d-a7f1-884ed7a14372">
<br>(This is how I envision how the bundle offers on the landing page should look like when the project is finished)
<br>The bundles on the landing page is placed there to get the visitors attention and hopefully get them to buy some of the products.

### Shop
<img width="627" alt="shop_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/dd6ae674-9f00-46c4-b666-335a584e983b">
<br>(This is how I envision the shop page when the project is finished)

### About page
<img width="627" alt="aboutpage_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/748e374a-effb-4654-b17a-0942a32e0cb2">
<br>(This is how I envision the about page when the project is finished)
<br>The about page is there to get the users attention, to give the users more understanding in why this shop has decided to sell this particular coffee and what positive changes the users may be able to contribute with when buying coffee from us.

### Register / Sign in page
<img width="285" alt="signin_mobile" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/97ab243f-0464-467e-b5e6-a01098cf6641">
<br>(This is how I envision the sign in/sign up page when the project is finished)
<br>I want the customers to be able to see more from us when registering and signing up for our newsletters. Also to give the users the ability to save their personal information, so that when they purchase something, their personal information is aready there.

## Design
I decided to have a dark themed website as I feel that it resembles the dark coffee and gives the site a nice feeling. The links also have a nice touch with the bright colors from the Ethiopian flag, green, yellow and red.
<br>
<br>
The homepage gives the users a small introduction about this business and also states the favorite coffees. For the users to get interested in buying some of those coffees. Or get interested in seeing what more this business has to offer.

## SEO
I am going to develop this project and make it as SEO smart as possible, since the project is far from done, I have not come to that point yet.

## Testing
You will find all of the information about how I did my testing in the TESTING.md file when the project is finished.

## Bugs

### Unfixed bugs
When setting the DEBUG = False my css is not loading properly from the CLI. Everything is working in the deployed link from Heroku but not in via the CLI, I've been in contact with a tutor regarding this and been told that the problem may be because I have another project in Cloudinary and may have to create a new Cloudinary account to get it to work.
<br>
For now I was adviced that if I don't want to create a new account, I can just continue as before and disable DEBUG when needing to edit my project, as my project works fine via the deployed link.

## Deployment 

### Deploy to Heroku
1. Log in to Heroku and create an App.
2. On the deploy tab, choose GitHub as the deployment method.
3. Select your repo name and click search.
4. Connect.
5. Select the branch you want to deploy and click Deploy Branch.
6. When the process is done. Open App on top of the page to access the app.
<br>
<br>
You can find the deployed link here https://kaffa-coffee-1c360e949e52.herokuapp.com/
## Credits

### Content


### Media 
The images for this project was taken from https://www.pexels.com/ 

