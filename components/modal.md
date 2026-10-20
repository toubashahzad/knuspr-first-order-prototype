# Modal system

**Functions:** `openModal(key)`, `closeModal()`, `modalHtml()` · **State:** `S.modal`

One renderer for every pop-up: postcode check, Delivery, address, contact, slot grid, payment, vouchers info, replacements info, product detail.

- Scrim behind, Escape and the × close it, focus returns to the button that opened it.
- A modal can have a fixed footer (product detail bar, Save buttons).
- Bottom sheet on phones, centred dialog on desktop.
