# 🔐 Secure Spring Boot Notes API

This project is a fully secured **Spring Boot backend application** that powers the `notes-app`. It demonstrates robust API protection using advanced Spring Security features such as:

- ✅ CSRF (Cross-Site Request Forgery) Protection  
- 🔐 JWT (JSON Web Token) Authentication  
- 🌍 CORS (Cross-Origin Resource Sharing) Configuration  
- 🛂 OAuth2 Support  
- 🔒 Full Role-Based Access Control

---

## ✨ Features

- Spring Boot Security integration for comprehensive backend protection
- JWT token-based authentication (secure, stateless sessions)
- Custom `AuthTokenFilter` and security chain for granular control
- CSRF tokens enabled for all state-changing HTTP operations
- CORS configured for controlled access from frontend clients
- OAuth2 ready (extendable)
- All endpoints require frontend authentication to access secured resources

---

## 📦 Tech Stack

- Java 17+
- Spring Boot 3.x
- Spring Security
- JWT
- OAuth2
- Maven
- RESTful API

---



## 🔐 Authentication Flow

- API endpoints are protected — only accessible after authentication
- Frontend clients must log in and attach a valid JWT token in request headers
- CSRF protection is enabled for sensitive actions
- Unauthorized or invalid token access will result in proper HTTP errors

---

## 🚀 Future Enhancements



---

## 📄 License

This project is licensed.

---

## 🙌 Contributions


---

## ✉️ Contact

Aina, Oluwatade  
Full Stack Software Engineer  
📧 tade55@yahoo.com  
GitHub: [@tade55](https://github.com/tade55)

