# NadBooks Backend API Documentation

This repository contains the **API documentation and client collection** for the NadBooks backend service. The documentation is designed to be used with **YAAK**, a modern API client, to make testing and exploration of the API straightforward.

---

## 📦 Repositories

* **Backend API (source code)**
  [https://github.com/plutack/nadbooks-backend](https://github.com/plutack/nadbooks-backend)

* **API Documentation & Client Collection (this repo)**
  [https://github.com/plutack/nadbooks-backend-API-documentation](https://github.com/plutack/nadbooks-backend-API-documentation)

---

## 🧰 Client of Choice: YAAK

We use **YAAK** as the recommended API client for interacting with the NadBooks backend.

### Why YAAK?

* Clean, modern UI
* Git-friendly collections
* Extensible via plugins
* Easy environment and secret management

### Download YAAK

👉 [https://yaak.app](https://yaak.app)

---

## 🚀 Getting Started

Follow the steps below to get up and running quickly.

### 1️⃣ Clone This Repository

```bash
git clone https://github.com/plutack/nadbooks-backend-API-documentation.git
cd nadbooks-backend-API-documentation
```

---

### 2️⃣ Install & Open YAAK

1. Download and install YAAK from [https://yaak.app](https://yaak.app)
2. Open YAAK on your machine

---

### 3️⃣ Import the API Collection

In YAAK:

1. Click **Import**
2. Choose **Import from Folder / Repository**
3. Select the cloned `nadbooks-backend-API-documentation` directory

This will load all predefined requests, environments, and variables into YAAK.

---

### 4️⃣ Configure the Encryption Key 🔐

Some API endpoints require an **encryption key** to function correctly.

* The encryption key is **not committed** to this repository for security reasons.
* You will need to obtain this key directly from the project maintainer.

Once you have the key:

1. Open the environment settings in YAAK
2. Locate the variable for the encryption key (e.g. `ENCRYPTION_KEY`)
3. Paste the provided value
4. Save the environment

> ⚠️ Do not commit or share this key publicly.

---

## 🌍 Environments

The collection supports multiple environments (depending on setup), such as:

* **Local** – for running the backend locally
* **Development / Staging** – for hosted test environments

Make sure the selected environment matches the backend instance you are targeting.

---

## 📚 API Coverage

The documentation covers key backend functionality, including but not limited to:

* Authentication & Authorization
* User management
* Books & catalog management
* Admin-only endpoints
* Role-based access control (RBAC)

Each request in YAAK includes:

* HTTP method and endpoint
* Required headers
* Request body examples (where applicable)
* Expected responses

---

## 🛠 Backend Development Reference

If you are working on the backend itself, refer to the main backend repository:

👉 [https://github.com/plutack/nadbooks-backend](https://github.com/plutack/nadbooks-backend)

That repository contains:

* Project setup instructions
* Environment variable definitions
* Database and migration details
* Application architecture

---

## 📩 Support / Access

If you need:

* The encryption key
* Access to restricted environments
* Clarification on any endpoint

Please contact the project maintainer directly.







