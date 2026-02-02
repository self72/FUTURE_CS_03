# FUTURE_CS_03


# 🔐 API Security Risk Analysis Report

This project analyzes security risks in publicly accessible REST APIs using **Postman**.

---

## 🔗 APIs Tested

Base URL:

```
https://dummyjson.com
```

* `/users`
* `/products`
* `/carts`
* `/recipes`
* `/comments`
* `/todos`

---

## ⚠️ Key Security Risks

* No authentication or authorization
* Sensitive data exposure
* Missing rate limiting
* Excessive data exposure
* No input validation

---

## 📊 Risk Severity

* **High:** Authentication issues, sensitive data exposure
* **Medium:** Rate limiting, data overexposure
* **Low:** Input validation

---

## 🛡️ Recommendations

* Use JWT / OAuth 2.0
* Mask sensitive fields
* Apply rate limiting
* Minimize response data

---

## 🧰 Tools

* Postman
* REST API
* JSON

