# Restaurant Service

## 1. Purpose

The Restaurant Service is one of the microservices in the Food Delivery application.

Its responsibility is to manage and provide:

- Restaurant information
- Restaurant availability
- Menu information
- Food-item information
- Food-item availability

The Restaurant Service is developed and tested independently before connecting it with the other microservices.

---

## 2. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Flask | REST API framework |
| JSON | API request/response data format |
| In-Memory Data | Stores restaurant and menu information |
| VS Code | Development environment |
| Git | Version control |

---

## 3. Project Structure

```text
restaurant-service/
│
├── app.py
├── requirements.txt
├── README.md
│
└── tests/
    └── test_restaurant.py