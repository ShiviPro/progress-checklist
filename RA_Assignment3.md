# RA Assignment 3 Checklist
## Routes:
- Create two routes:
  - [x] `ProductListing`: Displays a list of products with an option to add them to the cart.
  - [x] `Cart`: Displays the list of products added to the cart.

## Global Cart State:
- [x] Use React's `useContext` to create a `CartContext` for managing the cart state globally.
- [x] The cart should update when products are added from the `ProductListing` page.

## CartStatus Component:
- [x] Create a `CartStatus` component to display the total number of items in the cart.
- [x] Place this component in the navbar so it is visible on all pages.

## Functionality:
- On the `ProductListing` page:
  - [x] Display a list of products with their names, prices, and an "Add to Cart" button.
  - [x] When a product is added, it should be reflected in the cart.
- On the `Cart` page:
  - [x] Display all products added to the cart with their details.
  - [x] Show a message if the cart is empty.

## Navigation:
- [x] Add navigation links in the navbar to navigate between the `ProductListing` and `Cart` pages.

## Refactor
- [ ] Refactor code to make it clean, readable and more intuitive.
