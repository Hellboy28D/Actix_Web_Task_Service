🚀 Actix Web Task Service

A lightweight task management REST API built with Rust and Actix Web</b>
> Fast • Minimal • RESTful • Async

⸻

📖 Overview

This project is a RESTful task management backend built using Rust and Actix Web.

The goal of this project was to explore:

* Backend development in Rust
* Building asynchronous APIs
* REST architecture
* Request handling
* Structuring scalable Rust projects

The API provides task management functionality through standard CRUD operations.

⸻

✨ Features

✅ Create tasks

✅ Read tasks

✅ Update tasks

✅ Delete tasks

✅ JSON request/response handling

✅ Lightweight backend structure

✅ Async request processing using Actix

⸻

🛠 Tech Stack

Layer	Technology
Language	Rust
Framework	Actix Web
Serialization	Serde
API Style	REST

⸻

📁 Project Structure

Actix_Web_Task_Service/
│
├── src/
│   ├── main.rs
│   └── routes.rs
│
├── Cargo.toml
├── Cargo.lock
├── .gitignore
└── README.md

⸻

🚀 Getting Started

Clone the repository:

git clone https://github.com/Hellboy28D/Actix_Web_Task_Service.git

Move into project directory:

cd Actix_Web_Task_Service

Run the server:

cargo run

The server starts locally:

http://127.0.0.1:8080

⸻

📚 API Endpoints

Get Tasks

GET /tasks

Returns all tasks.

⸻

Create Task

POST /tasks

Example request:

{
    "task_name":"Build API",
    "task_status":"In Progress"
}

⸻

Update Task

PUT /tasks/{id}

Updates an existing task.

⸻

Delete Task

DELETE /tasks/{id}

Deletes a task.

⸻

🧠 Learning Outcomes

While building this project I explored:

* Rust ownership and borrowing
* Async programming concepts
* REST API design
* Structuring backend services
* Request routing and handlers
* Error handling patterns

⸻

⚠️ Current Limitations

* No authentication
* No database integration
* Minimal validation
* Learning/demo project

⸻

🔮 Future Improvements

* JWT Authentication
* PostgreSQL integration
* Docker support
* Request validation
* API documentation with Swagger
* Unit and integration tests

⸻

🤝 Contributing

Contributions and suggestions are welcome.

Fork the repository and create a pull request.

⸻

📄 License

This project is open source and available under the MIT License.

⸻


Built with ❤️ using Rust + Actix Web
