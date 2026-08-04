# Authentication

POST /auth/register

POST /auth/login

---

# Flowers

GET /flowers

GET /flowers/[id]

---

# Bouquets

GET /bouquets

GET /bouquets/[id]

POST /bouquets/custom

---

# Cart

GET /cart

POST /cart/items

PATCH /cart/items/[id]

DELETE /cart/items/[id]

---

# Orders

POST /orders

GET /orders/[id]

---

# Users

GET /users/me

PATCH /users/me

---

# Admin

GET /admin/users

PATCH /admin/users/[id]

GET /admin/orders

PATCH /admin/orders/[id]