# G2Market Database Design

## Tables

### Users

- id
- name
- email
- phone
- country
- password
- role

---

### Warehouses

- id
- warehouse_name
- address
- city
- country

---

### Virtual Addresses

- id
- user_id
- warehouse_id
- unique_code

---

### Packages

- id
- user_id
- tracking_number
- weight
- dimensions
- status

---

### Shipments

- id
- package_id
- courier
- cost
- tracking_number
- status

---

### Payments

- id
- user_id
- amount
- currency
- payment_method
- status
