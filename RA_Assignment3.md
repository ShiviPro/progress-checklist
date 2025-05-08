# RA Assignment 3 Checklist
## Routes:
- Create two routes:
  - [x] `ProductListing`: Displays a list of products with an option to add them to the cart.
  ![image](https://github.com/user-attachments/assets/20e05db4-1810-4ed7-b3b3-7b2aa24aa454)

  - [x] `Cart`: Displays the list of products added to the cart.
  ![image](https://github.com/user-attachments/assets/71a3a75a-bfa7-4a03-950d-ef9fd71d78b8)


## Global Cart State:
- [x] Use React's `useContext` to create a `CartContext` for managing the cart state globally.
- [x] The cart should update when products are added from the `ProductListing` page.
![AddItemToCartDemo](https://github.com/user-attachments/assets/9ec1f5d5-14aa-4f6b-85d4-f0ba3cc26407)


## CartStatus Component:
- [x] Create a `CartStatus` component to display the total number of items in the cart.
- [x] Place this component in the navbar so it is visible on all pages.
      ![image](https://github.com/user-attachments/assets/856fc1d7-b36b-4446-adb8-06e2a57ea863)


## Functionality:
- On the `ProductListing` page:
  - [x] Display a list of products with their names, prices, and an "Add to Cart" button.
  - [x] When a product is added, it should be reflected in the cart.
- On the `Cart` page:
  - [x] Display all products added to the cart with their details.
  - [x] Show a message if the cart is empty.
![image](https://github.com/user-attachments/assets/aacd886c-40a7-40e4-9a81-98936d575f59)

## Navigation:
- [x] Add navigation links in the navbar to navigate between the `ProductListing` and `Cart` pages.
![image](https://github.com/user-attachments/assets/f348fe78-5292-42e6-ad4e-fe11b7e03512)

## Refactor:
- [x] Refactor code to make it clean, readable and more intuitive.

## Code Link:
- [x] Code can be found on [Stackblitz](https://stackblitz.com/edit/ra-assignment3)

## Video:
 - [x] [Explanation Video](https://youtu.be/ckkXD43_feM)

## Branding:
- [x] App name based on an abstract theme,
- [x] Favicon based on the app name.
