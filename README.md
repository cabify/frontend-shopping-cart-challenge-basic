**Besides providing exceptional transportation services, Cabify also runs a physical store which sells (only) 3 products:**

The current prices of the products are the following:
```
Code         | Name                |  Price
-------------------------------------------------
TSHIRT       | Cabify T-Shirt      |  20.00€
MUG          | Cafify Coffee Mug   |   5.00€
CAP          | Cabify Cap          |  10.00€
```

Our top UI engineer has already made an initial implementation of the store with vanilla html and css, but it lacks the implementation

![Example image](./example.png?raw=true)

## Challenge

**Using the framework/library of your choice you have to:**
- Decompose the markup in components or whatever it suits you better to make it a production ready App.
- Implement the shopping cart logic with the following **requisites**:
  - Add/Remove product card items using the +/- buttons.
  - Calculate the totals of each product and the summary total accordingly.
  - All totals in order summary should be updated whenever a product is added or removed.

**Take into account the following aspects:**
- Have notes attached, explaining the solution and why certain things are included and others are left out.
- Deliver production ready code.
- Provide a solution that could be easy to grow and easy to add new functionality.
- You can add any UX / UI improvements you consider, but we are going to focus on the requested features.
We value succinctness.
- When in doubt, act as a product owner

**Bonus Points**

There are bonus points. That means that are not mandatory, up to you if you want to implement them (one or both) or not.

1. Product Detail modal
  * Our UI engineer hadn't time either to work on the product details modal which you can see in the `/bonus` folder. It would be a plus if you could implement it.

2. Discounts
We would like to add some discounts to our products. Choose one or both and add them in your implementation:
  * 2-for-1 promotions: buy two of the same product, get one free, applied to `MUG` items.
  * bulk discounts: buying 3 or more of `TSHIRT` product, the price of that product is reduced 5%. E.g., if you buy 3 or more `TSHIRT` items, the price per unit should be 19.00€.
