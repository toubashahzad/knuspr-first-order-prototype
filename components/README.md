# Components

The prototype is one HTML file (`index.html`), but it is built from a small set of reusable components. Each is a render function that returns HTML from the app state `S`, so every screen uses the same pieces.

| Component | File | Used on |
| --- | --- | --- |
| Header and shopping row | [header.md](header.md) | Every page |
| Postcode check | [postcode-check.md](postcode-check.md) | Landing |
| Product card | [product-card.md](product-card.md) | Shop, recommendations |
| Product detail pop-up | [product-detail.md](product-detail.md) | Shop |
| Stepper | [stepper.md](stepper.md) | Cards, pop-up, cart, checkout |
| Progress to the minimum | [progress.md](progress.md) | Toast, drawer, full cart |
| Cart drawer and full cart | [cart.md](cart.md) | Cart |
| Delivery pop-up (Where + When) | [delivery.md](delivery.md) | Header, checkout |
| Checkout | [checkout.md](checkout.md) | Checkout |
| Order summary and voucher | [summary.md](summary.md) | Cart, checkout, confirmation |
| Modal system | [modal.md](modal.md) | All pop-ups |

Shared rules across components:
- Anything that opens a pop-up uses a right chevron, not a down arrow.
- Prices: "ca." only on totals that include weighed items; the amount you pay is always one fixed number.
- The first-order discount reads "50% off your first order, up to €20" and is applied at checkout.
- Light and dark mode come from CSS tokens on `:root`.
