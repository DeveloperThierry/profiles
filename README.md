# Profile Management API

A robust and scalable backend REST API built with NestJS to manage user profile data seamlessly.

## 🚀 Features

*   **RESTful Architecture:** Clear separation of concerns utilizing NestJS controllers, modules, and services.
*   **Data Validation:** Strict request body validation using Data Transfer Objects (DTOs).
*   **Profile Management:** Full CRUD operations handler for creating, reading, updating, and deleting profiles.
*   **Modular Design:** Highly structured codebase designed for easy scalability and maintenance.

---

## 🛠️ Installation

Follow these steps to set up the project locally on your machine.

### Prerequisites

*   Node.js (v18.x or higher recommended)
*   npm

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/DeveloperThierry/profiles.git
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

---

## ⚙️ Usage

You can interact with the API using the following commands and endpoints.

### Running the Application

```bash
# Development mode
npm run start

# Watch mode (auto-reload on changes)
npm run start:dev

# Production mode
npm run start:prod
```

### Key API Endpoints

| Method | Endpoint      | Description                      |
| :---   | :------------ | :------------------------------- |
| `GET`  | `/profiles`   | Retrieves a list of all profiles |
| `GET`  | `/profiles/:id` | Retrieves a single profile by ID |
| `POST` | `/profiles`   | Creates a new user profile     |
| `PUT`  | `/profiles/:id` | Updates an existing profile by ID|
| `DELETE`| `/profiles/:id` | Deletes a profile by ID          |

---

## ✅ Testing

Run the following command to execute the test suite:

```bash
npm run test
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.
