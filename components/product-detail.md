# Product detail pop-up

**Modal key:** `pd` · **Functions:** `openPd(id)`, `pdFoot()` · **State:** `S.pdId`, `S.pdPairs`

One column, top to bottom:
1. Photo
2. Name
3. Size ("1 kg")
4. Price with deal tag, and price per kg / litre / piece on the right
5. Labels with names (Organic, Vegan, Gluten-free)
6. *Often bought with*: three items not already in the cart, fixed when the pop-up opens, each with the normal "+ Add" / stepper
7. *Product details*: brand, country of origin, own brand, deposit, weighed item

**Fixed bottom bar:** "+ Add" first, then the stepper. It never moves while scrolling, and every tap updates the cart with the pop-up still open.
