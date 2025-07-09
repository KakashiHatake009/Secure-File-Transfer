# 🔐 SecureShare

A full-stack secure file sharing web application designed to demonstrate best practices in secure development and self-pentesting.

---

## 📌 Overview

**SecureShare** allows users to securely upload, share, and manage files with role-based access control and audit logging. It is built from the ground up with security in mind — covering authentication, authorization, encrypted file handling, and vulnerability prevention.

---

## 🚀 Features

### 🛡️ Security
- Secure password storage (bcrypt)
- JWT-based authentication + refresh tokens
- Optional 2FA (TOTP or email codes)
- Rate limiting on sensitive routes
- CSRF protection and input sanitization
- File validation (type, size, scanning)
- Expiring signed download URLs

### 📁 File Handling
- Secure uploads with renamed file storage
- File sharing with optional password and expiry
- Role-based access control (RBAC)
- Audit logs for file access/download

### 👥 User Roles
- **Admin**: Manage users and view global logs
- **User**: Upload/download/share files, view their own access logs

---

## 💻 Tech Stack

| Layer         | Technology                            |
|---------------|----------------------------------------|
| Frontend      | React, Tailwind CSS                    |
| Backend       | Node.js, Express (or Flask/FastAPI)    |
| Database      | PostgreSQL (or MongoDB)                |
| Auth          | JWT + Refresh Tokens, bcrypt, 2FA      |
| Storage       | AWS S3 (or local file system)          |
| Security Tools| Helmet, CORS, Rate Limiting, CSURF     |

---



