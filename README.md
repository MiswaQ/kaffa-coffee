# Kaffa Coffee

Welcome to Kaffa Coffee, an Ethiopian coffee shop built as part of my e-commerce specialization project portfolio for the Full Stack Software Development diploma at Code Institute. This webshop is designed for coffee lovers, offering a taste of "the kingdom of Kaffa," the birthplace of coffee. Our webshop is straightforward, featuring a shop page, about page, and a signup page for users to receive newsletters and updates on new coffee arrivals.

![homepage-kaffa-coffee](https://github.com/MiswaQ/kaffa-coffee/assets/121927777/7e1d6bb2-ad89-43ac-ac63-113cb577ffbc)

## Planning

At the beginning of this project, I considered the following questions to guide the development of the application:

- **Who is the customer?** B2C - Business to Customer
- **What will they buy?** Coffee products
- **How will they pay?** Single payment

With these considerations, I planned the e-commerce application to include:

- **E-commerce application types:** B2C, Products, Single payments
- **Features:** Easy Payment, User Authentication, Social Media Authentication, Search Functionality, Product Descriptions, Ratings/Reviews, Contact Form, Shopping Cart, Payment System, and Wishlist
- **Database tables:**
  - **User:** username, email, password
  - **Product:** name, image, price, description, size, rating
  - **Order:** user, total, full_name, address
  - **OrderItem:** order, product, quantity
  - **Wishlist:** user, product

## Features

### Homepage

The homepage of Kaffa Coffee is designed to welcome users with a visually appealing layout with a "shop now" button to let the customer drop right in to the coffee shop. It features:

- **Header:** Navigation menu with links to the shop, about page, user account, and wishlist.
- **Featured Products:** Display of popular coffee products with images, prices, and ratings.
- **Signup:** Form for users to sign up.
- **Footer:** Contact information, social media links, and additional resources.

### Shop Page

The shop page showcases our coffee products with detailed descriptions, prices, and user ratings. Users can search for products, filter by category, add items to their shopping cart, and add products to their wishlist for future reference.

### About Page

Did not have time to make one.

### User Account

Users can create an account, log in, and manage their profiles. They can view their order history, update personal information, and save favorite products in their wishlist.

### Wishlist

Users can add their favorite coffee products to their wishlist, allowing them to save items for future purchases or to keep track of their preferred products.

## Design

### Colors

The color scheme of Kaffa Coffee is inspired by the rich and warm tones of Ethiopian coffee. The primary colors used are:

- **Primary Color:** #6F4E37 (Coffee Brown)
- **Secondary Color:** #D9B382 (Golden Beige)
- **Accent Color:** #FFFFFF (White)

### Fonts

The fonts used in the Kaffa Coffee project are:

- **Primary Font:** 'Playfair Display', serif;
- **Secondary Font:** 'Lato' sans-serif

These fonts were chosen for their readability and modern aesthetic, enhancing the user experience on the site.

## How to Get Started

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/MiswaQ/kaffa-coffee.git
    cd kaffa-coffee
    ```

2. **Install the dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

3. **Run the application:**

    ```sh
    python manage.py runserver
    ```

4. Open your browser and navigate to `http://127.0.0.1:8000/` to view the site.

## Credits and Contact

### Code

I want to thank my instructor and peers for their feedback, which helped improve the design and functionality of this project.

### Content and Media

- Images sourced from free stock photo websites and my own photography.
- Text content created by me, inspired by Ethiopian coffee culture.

### Contact

For any inquiries or feedback, please contact me at **miswaq@gmail.com**.

This project was created for the PP5 Project for the Full Stack Software Developer program with Code Institute.

Zekroum Abdulrahman Aregai, 2024
