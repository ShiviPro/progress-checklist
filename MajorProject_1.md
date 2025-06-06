# Major Project 1 (Mizuki Hanae)

## Code
Have a look at my code in this [GitHub Repo](https://github.com/ShiviPro/mizuki-hanae)

## Home Page
- [x] A landing page with a list of featured categories.
  - [x] If I click on any one of the categories I will be redirected to the product list page with that selected category.

## Product Listing Page
- [x] A product listing page where all the products are listed with a section of filters.
- [x] Product Cards should have product image, product name, product price, product rating, add to cart button and add to wishlist (button/icon).
- [x] Multiple filters on the product listing page including.
  - [x] Price: A slider for price.
  - [x] Category: A checkbox with various categories according to the theme.
  - [x] Ratings: A slider for ratings.
- [x] A button to clear filters from where you can clear all the applied filters.
- On the product cards, you should see two call-to-action buttons,
  - [x] Add to Cart: "Add to Cart" primary button should be present.
  - [x] Add to Wishlist: "Add to Wishlist" secondary button or "Wishlist" secondary icon button should be present.

*__Todo__: Please look into this: changing the filters on the Products page is not reflected in the url with modified values of search params.* 

## Sort by Price
- [x] Along with the multiple filters on the product listing page on the sidebar, add a feature to sort products by price,

  - [x] Price: A radio button to sort from low to high.
  - [x] Price: A radio button to sort from high to low.

## Product Detail Page
- [x] If you click on any product you should be redirected to a single product page with all its details & the "Add to Cart" & "Add to Wishlist" buttons.

## Wishlist Management

- [x] From the navbar, you can navigate to your wishlist where all the products that you liked and wish to buy in the future are mentioned.
  - [x] On the product card,
    - [x] You can remove the item from the wishlist
    - [x] Add the item to the cart
      - [ ] If the cart already contains that item, it should only increase the quantity.

## Cart Management
- [x] From the navbar, you can navigate to the cart where all the products that you want to buy are mentioned.
  - On the product card,
    - [x] You can see the quantity of a particular product.
    - [x] You can Increase or Decrease the quantity of a particular product.
    - [ ] Remove the product from the cart
    - [ ] Add the product to the Wishlist
  - [ ] You can see the price details card of the cart containing a button to checkout which will show the total price of the products with its quantity.

## Address Management
- [ ] You can add multiple addresses, update or delete them.
- [ ] You can choose a single address to deliver the order.

## Checkout
- [ ] Once you choose the address, you can click on the checkout button which would show the order summary and a message - "Order Placed Successfully." Save orders placed in your backend.

## User Profile
- [ ] You can see the user profile with details containing the name, email Id, phone number, address, etc. This data should be static.
- [ ] You can give the option to Add new address from this page.
- [ ] You can give the option to see the order history from this page. Order History is all the orders placed previously.

## Loading & Alerts
- [ ] You can see loading messages when the data i.e. the products are loading.
- You can see the acknowledgement alerts whenever you,
  - [ ] Add item to the cart
  - [ ] Remove Item from the cart
  - [ ] Increase or Decrease item in the cart
  - [ ] Move an item from the cart to the wishlist
  - [ ] Add item to the wishlist
  - [ ] Remove Item from the wishlist
  - [ ] Move an item from wishlist to cart

## Search
- [ ] You can search for an item from the product list via the input text box on the header navbar.
