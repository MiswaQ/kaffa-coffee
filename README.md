# Kaffa Coffee

Kaffa Coffee is a potential Ethiopian coffee shop that I have built as my e-commerce specialization Project Portfolio 5 for my diploma in Full Stack Software Development at Code Institute. 
This webshop is built for coffee lovers, from “the kingdom of kaffa” (i.e. Ethiopia), where the origin of coffee started. The webshop is simple and straight to the point, with a shop page, about page and of course a sign up page so that the users can sign up for newsletters and get all the updates about the business and if there is any new coffee available. 
<img width="627" alt="homepage_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/d8e4dd40-8c27-437d-b5ca-c70f02e52cb9">
<br>_(This is how I envision the landing page when the project is finished)_

## Planning
At the beginning of this project I started out with these three questions to get a better idea of what type of application I wanted to build, and the outcome is as follows:
<br>
<br>
**Who is the customer?** B2C - Business to Customer
<br>
**What will they buy?** Products
<br>
**How will they pay?** Single payment
<br>
<br>
Then I followed up with these three questions to plan my e-commerce application:
<br>
- **Which e-commerce application types apply to this online business?**
  <br> B2C, Products, Single payments
- **With the e-commerce application types in mind, what kind of features might be included within the business website?**
  <br> Easy Payment, Authentication System for users to log in/out and access their relevant data, Authentication with social accounts for easier registration, Search Function, Images, Product Description, Ratings/Reviews, Contact Form, Shopping Cart and Payment System
- **What tables of data would my database need, and what data might be included in these tables?**
  <br> User: username, email, password
  <br> Product: name, image, price, description, size, rating
  <br> Order: User, total, full_name, address
  <br> OrderItem: Order, Product, quantity

## Features
I have just started off with my project. Because of medical leave and parental leave I have lost some time and fallen behind.
But this is approximently the way I want it to look when the project is finished. All of the images comes from my wireframes and this is how I am imagin it to look like.
<br>
<br>
### Navigation bar
<img width="627" alt="navbar_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/8fac87df-08d4-4347-9a41-c1094715170a">
<br>_(This is how I envision the navigation bar on desktop when the project is finished)_
<br> Simple and easy to use.
<br>
<br>
<img width="288" alt="navbar_mobile" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/cc6aa6b3-a4cb-40b0-8a88-60c278326c05">
<br>_(This is how I envision the navigation bar on smaller devices when the project is finished)_

### Landing page
<img width="627" alt="homepage_desktop" src="https://github.com/MiswaQ/kaffa-coffee/assets/121927777/35ba6d45-4745-4539-af0d-33d2a8f95c36">
<br>_(This is how I envision the landing page when the project is finished)_

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

## Credits

### Content


### Media 
The images for this project was taken from https://www.pexels.com/ 

