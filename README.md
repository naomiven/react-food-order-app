# react-food-order-app

Food order app to practice various React hooks

Built with:

```sh
npm -v
8.1.2
node -v
v16.13.1
```w

## useEffect

- Used for showing & hiding the Cart Modal

## useContext

- `CartContext` stores all states & functions for the cart. Eg., `items`, `totalAmount`, `addItem`, `removeItem`.
  - Used for adding an item to cart
- `CartProvider` manages the cart context data. It is used as a wrapper to all components that want access to the context.
