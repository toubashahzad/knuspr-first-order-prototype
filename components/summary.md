# Order summary and voucher

**Functions:** `finalCosts(t, done)`, `ticketHtml(t)`, `totals()`

Summary lines, top to bottom:
- Items, Bottle deposit, Delivery (Free, first order)
- First-order discount, with "50% of your order, up to €20" underneath
- Rider tip
- **Order total**
- Weight buffer (its own line, with an info button)
- **You pay** (one fixed amount)
- Green pill outside the sum: "You save €X on this order"

Voucher card: "€10.57 off now. Add €18.85 to get the full €20." The discount is 50% of the order up to €20 and is only taken off at checkout; the cart says "you're eligible".
