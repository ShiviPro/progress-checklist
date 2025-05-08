# RA Assignment 3 Checklist
## Routes:
- Create two routes:
  - [x] `ProductListing`: Displays a list of products with an option to add them to the cart.
  ![image](https://github.com/user-attachments/assets/098d0030-318a-4829-8fb7-8b715426ac7f)

  - [x] `Cart`: Displays the list of products added to the cart.
  ![image](https://github.com/user-attachments/assets/26aaf1c9-0e2c-41c8-8384-48ef653903f5)


## Global Cart State:
- [x] Use React's `useContext` to create a `CartContext` for managing the cart state globally.
- [x] The cart should update when products are added from the `ProductListing` page.
![AddItemToCartDemo](https://github.com/user-attachments/assets/360c1829-912e-4b3d-bc1c-2fae219f1ece)


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
![image](https://github.com/user-attachments/assets/75654274-414e-47c3-95f8-ae3f29f38b08)

## Navigation:
- [x] Add navigation links in the navbar to navigate between the `ProductListing` and `Cart` pages.
![image](https://github.com/user-attachments/assets/99985d5d-5409-47ec-b294-672784bf138b)

## Refactor:
- [x] Refactor code to make it clean, readable and more intuitive.

## Code Link:
- [x] Code can be found on [Stackblitz](https://stackblitz.com/edit/ra-assignment3)

## Video:
 - [x] [Explanation Video](https://youtu.be/ckkXD43_feM)

## Branding:
- [x] App name based on an abstract theme,
- [ ] Favicon based on the app name.
