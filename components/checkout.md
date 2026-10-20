# Checkout

**Function:** `renderCheckout(t)` · **Gate:** `isReady(t)`, `payHint(t)`

One page, in order:
1. **Where:** *Your details* (first name, last name, phone, email; this creates the account) and the address. Each row shows a tick when complete.
2. **When:** Fastest, Bundled, Choose a time.
3. **Your items:** grouped by aisle, still editable.
4. **Payment:** Apple Pay (default), Google Pay, PayPal, Credit or debit card (opens card number, expiry, security code, name). The selected method shows "Will be charged €X".
5. **Offers and savings:** the first-order discount card.
6. **Tip your rider:** chips No tip, €1, €2, €3, €5.

The pay button names the method and stays disabled until everything is filled in; the line under it says what's missing next.
