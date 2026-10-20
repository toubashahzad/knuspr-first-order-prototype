# Knuspr first-order prototype

A clickable prototype for a product case study on Knuspr's first-time orders: getting a first-time customer from a part-filled cart to a placed order.

**Live demo:** https://toubashahzad.github.io/knuspr-first-order-prototype/

## What it shows

1. **Progress card on add.** Adding a product doesn't open the cart. A small card shows the item and progress to the €39 minimum, then fades out.
2. **Side cart.** Full-height panel with the minimum as a goal, quick-add suggestions, and every cost line settled: items, deposit, free first delivery, and the €20 welcome discount once €39 is reached.
3. **One-page checkout.** Headed sections instead of a stepper: address, delivery time (each slot shows its price), items you can still edit, payment. A sticky summary on the right.
4. **Card hold explained before payment.** Weighed items (fruit, veg, meat) can change price, so the page says how much is reserved and that the exact amount is charged after packing.

## How it's built

One `index.html`: HTML, CSS and vanilla JavaScript, no framework or build step. Products, prices and slots are example data inside the file. Cart state is kept in the browser's localStorage; "Start over as a first-time customer" resets it.

Built with Claude as a coding agent, then reviewed and corrected by hand.

Prices and products are examples. This is not affiliated with Knuspr, no order is placed and nothing is charged.

## Run locally

Open `index.html` in a browser.

## Components

See [components/](components/README.md) for the building blocks used in the prototype.
