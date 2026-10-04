# Delivery Service

## 1. Purpose

The Delivery Service is an independent microservice responsible for managing the delivery lifecycle of food orders.

It provides REST APIs to:

- Create a delivery
- Assign a delivery person
- Check delivery details
- Update delivery status
- Check the current delivery status

The service currently uses simple in-memory data storage.

---

## 2. Technologies Used

- Python
- Flask
- REST API
- JSON
- In-memory data storage

---

## 3. Project Structure

```text
delivery-service/
├── app.py
├── requirements.txt
├── README.md
└── tests/
    └── test_delivery.py