# Online Food Delivery Management System

## Group Members
- Student 1: _Rana Sudan
- Student ID: 202510331

- Student 1: _safa
- Student ID: 202511576

## Project Idea
An online food delivery information system connecting customers, restaurants, menu items, orders, payments, and delivery drivers.

## Scope
The project models customer registration, restaurant/menu management, order processing, payment recording, and delivery management. It does not implement a complete web/mobile application or real payment gateway.

## Main Classes
Customer, Restaurant, MenuItem, Order, OrderItem, Payment, Delivery, DeliveryDriver.

## Relationships
- Customer 1 — 0..* Order
- Restaurant 1 — 1..* MenuItem
- Order 1 — 1..* OrderItem
- OrderItem 0..* — 1 MenuItem
- Order 1 — 1 Payment
- Order 1 — 1 Delivery
- Delivery 1 — 1 DeliveryDriver

## Files
- documentation/report_1_project_description.pdf
- documentation/report_2_uml_class_diagram.pdf
- diagrams/uml_class_diagram.drawio
- diagrams/uml_class_diagram.png
