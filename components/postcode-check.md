# Postcode check

**Modal key:** `pc` · **State:** `S.zip`, `S.pcStep` (`ask` | `ok` | `no`) · **Helper:** `zoneOf(zip)`

Opens as soon as a new visitor lands, so nobody fills a cart for an area Knuspr can't deliver to.

- **Ask:** one postcode field, "Check postcode", and "Already have an account? Sign in". Validates 5 digits.
- **Yes:** "Yay, we deliver to Berlin 12107" with three chips: free first delivery, €20 minimum, 50% off your first order up to €20. Buttons: *Sign in or register*, *Start shopping*.
- **No:** "We don't deliver to 99999 yet" with the areas served. Buttons: *Browse anyway*, *Try another postcode*.
- The exact address is asked later, in the Delivery pop-up or at checkout.
