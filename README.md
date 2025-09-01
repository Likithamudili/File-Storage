🔒 Secure File Storage System

A secure file storage and sharing platform built with Python (Flask) and Hybrid Cryptography (AES + RSA). The system ensures that uploaded files are encrypted before storage and can only be decrypted with the correct user key. This project demonstrates Zero Trust Data Security principles, aligning with real-world needs for data confidentiality, availability, and resilience.

🚀 Features

Hybrid Cryptography

AES for fast, bulk data encryption.

RSA for secure key exchange.

User Authentication

Secure login with hashed passwords (Flask sessions / JWT).

File Operations

Upload, encrypt, download, and decrypt files securely.

Cloud Backup (Optional)

Store encrypted files on AWS S3 / Google Cloud Storage.

Logging & Monitoring

Tracks file operations and alerts on failed authentication attempts.

Scalable Design

Modular backend that can be extended for enterprise use.

🛠️ Tech Stack

Languages: Python

Frameworks: Flask, Cryptography (PyCrypto / Cryptography library)

Frontend: HTML, CSS, JavaScript (Bootstrap)

Database: SQLite / MySQL (for user authentication & logs)

Optional Cloud: AWS S3 / GCP Cloud Storage
