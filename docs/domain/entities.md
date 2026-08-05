# Domain Entities

## User

Represents a registered customer.

Responsibilities:

- authentication
- order history
- saved addresses

---

## Guest

Represents an anonymous customer.

Responsibilities:

- browse products
- create custom bouquet
- place an order

---

## Administrator

Represents an employee responsible for managing the application.

Responsibilities:

- manage users
- manage flowers
- manage bouquets
- manage categories
- manage orders

---

## Flower

Represents a flower available in the shop.

Contains:

- name
- price
- availability

---

## Bouquet

Represents a bouquet.

Can be:

- ready-made
- custom

Contains multiple flowers.

---

## Cart

Temporary customer basket.

Contains bouquets.

---

## Order

Represents a completed purchase.

Contains:

- bouquets
- customer
- delivery information
- payment status

---

## Address

Delivery address.

---

## Category

Represents bouquet or flower category.