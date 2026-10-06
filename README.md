# Awesome FastAPI 🚀

> A curated list of awesome FastAPI frameworks, packages, libraries, and software. 

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. If you want to suggest a package, open an issue or submit a Pull Request.

---

## 📑 Table of Contents

* [Official Resources](#-official-resources)
* [Boilerplates & Project Templates](#-boilerplates--project-templates)
* [Authentication & Security](#-authentication--security)
* [Database, ORM & Migrations](#-database-orm--migrations)
* [Validation & Serialization](#-validation--serialization)
* [GraphQL](#-graphql)
* [Admin Panels & Dashboards](#-admin-panels--dashboards)
* [Background Tasks & Message Brokers](#-background-tasks--message-brokers)
* [WebSockets & Real-time](#-websockets--real-time)
* [Caching & Rate Limiting](#-caching--rate-limiting)
* [Error Handling & Logging](#-error-handling--logging)
* [Testing & Quality Assurance](#-testing--quality-assurance)
* [DevOps, Deployment & Docker](#-devops-deployment--docker)
* [Extensions, Utilities & Middleware](#-extensions-utilities--middleware)
* [Community, Blogs & Tutorials](#-community-blogs--tutorials)

---

## 🌐 Official Resources
*Essential official links and community hubs.*
* [Official Website & Docs](https://fastapi.tiangolo.com/) - The home of FastAPI, with incredible interactive documentation.
* [Official GitHub Repository](https://github.com/fastapi/fastapi) - Star and contribute to the core framework.
* [FastAPI Discussions](https://github.com/fastapi/fastapi/discussions) - Ask questions and share ideas with the community.

---

## 🏗️ Boilerplates & Project Templates
*Jumpstart production-ready FastAPI applications.*
* [Full Stack FastAPI Template](https://github.com/fastapi/full-stack-fastapi-template) - Official full-stack template by Tiangolo (React, Docker, PostgreSQL, Traefik).
* [FastAPI Users Template](https://github.com/fastapi-users/fastapi-users) - Ready-to-use boilerplate with robust user management.
* [FastAPI Cookiecutter Stacks](https://github.com/cookiecutter/cookiecutter) - Various community-driven project structures.
* [FastAPI Production Template](https://github.com/Kludex/fastapi-template) - Clean and structured boilerplate by FastAPI core developer Kludex.

---

## 🔐 Authentication & Security
*User management, OAuth2, JWT tokens, and security utilities.*
* [FastAPI Users](https://github.com/fastapi-users/fastapi-users) - Ready-to-use and extensible user management module for FastAPI.
* [FastAPI Security](https://github.com/fastapi/fastapi) - Built-in security utilities (OAuth2, API keys, HTTP Basic).
* [Authlib](https://github.com/lepture/authlib) - The ultimate Python library for building OAuth, OpenID Connect, and JWT.
* [FastAPI Keycloak](https://github.com/jowilf/fastapi-keycloak) - Keycloak integration for FastAPI security.

---

## 💾 Database, ORM & Migrations
*Interacting with databases and managing models asynchronously.*
* [SQLModel](https://github.com/fastapi/sqlmodel) - SQL databases in Python, designed for FastAPI, built by Tiangolo using SQLAlchemy and Pydantic.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) - An easy-to-use async ORM inspired by Django.
* [Encode Databases](https://github.com/encode/databases) - Async database support for SQLAlchemy, PostgreSQL, MySQL, and SQLite.
* [Prisma Client Python](https://github.com/prisma/prisma-client-py) - Auto-generated and type-safe ORM for FastAPI.
* [Alembic](https://github.com/sqlalchemy/alembic) - Database migration tool for SQLAlchemy.

---

## 📝 Validation & Serialization
*Leveraging Pydantic and data validation.*
* [Pydantic](https://github.com/pydantic/pydantic) - Data validation using Python type hints (the core of FastAPI).
* [Pydantic Extra Types](https://github.com/pydantic/pydantic-extra-types) - Extra Pydantic types like phone numbers, color codes, etc.

---

## 🛰️ GraphQL
*Building GraphQL endpoints with FastAPI.*
* [Strawberry GraphQL](https://github.com/strawberry-graphql/strawberry) - Python GraphQL library based on dataclasses with native FastAPI integration.
* [Ariadne](https://github.com/mirumee/ariadne) - Schema-first Python library for implementing GraphQL servers.

---

## 🎨 Admin Panels & Dashboards
*Administrative interfaces and UI tools for FastAPI.*
* [SQLAdmin](https://github.com/aminalaee/sqladmin) - Admin interface for SQLAlchemy models in FastAPI/Starlette.
* [FastAPI Admin](https://github.com/fastapi-admin/fastapi-admin) - An admin dashboard based on Tortoise ORM and AdminLTE.
* [FastAdmin](https://github.com/fastadmin-org/fastadmin) - Modern full-stack admin panel built for FastAPI.

---

## ⚙️ Background Tasks & Message Brokers
*Handling asynchronous operations and message queues.*
* [Celery](https://github.com/celery/celery) - Distributed task queue seamlessly integrated with FastAPI.
* [FastStream](https://github.com/airtai/faststream) - Powerful framework for building asynchronous microservices interacting with brokers like RabbitMQ, Kafka, and Redis.
* [ARQ](https://github.com/samuelcolvin/arq) - Job queues in Python with asyncio and Redis.
* [Taskiq](https://github.com/taskiq-python/taskiq) - Distributed asynchronous task queue for Python with dependency injection.

---

## ⚡ WebSockets & Real-time
*Real-time communication tools.*
* [FastAPI WebSockets](https://fastapi.tiangolo.com/advanced/websockets/) - Native support for bidirectional real-time communication.
* [Socket.IO Python](https://github.com/miguelgrinberg/python-socketio) - Socket.IO server implementation compatible with ASGI/FastAPI.

---

## 🚦 Caching & Rate Limiting
*Optimizing performance and protecting endpoints.*
* [FastAPI Cache](https://github.com/long2ice/fastapi-cache) - Lightweight caching decorator for FastAPI endpoints.
* [FastAPI Limiter](https://github.com/long2ice/fastapi-limiter) - Rate limiter for FastAPI using Redis.
* [SlowAPI](https://github.com/laixintao/slowapi) - Rate limiter for FastAPI/Starlette inspired by Flask-Limiter.

---

## 🪵 Error Handling & Logging
*Tracking application behavior and tracking errors.*
* [Sentry Python](https://github.com/getsentry/sentry-python) - Real-time error tracking and performance monitoring for FastAPI.
* [Loguru](https://github.com/Delgan/loguru) - Python logging made simple and enjoyable.
* [FastAPI Exception Handlers](https://fastapi.tiangolo.com/tutorial/handling-errors/) - Built-in customizable exception routing.

---

## 🧪 Testing & Quality Assurance
*Ensuring robust and reliable APIs.*
* [Pytest](https://github.com/pytest-dev/pytest) - The standard testing framework for Python.
* [HTTPX](https://github.com/encode/httpx) - A fully featured HTTP client for Python 3, essential for FastAPI `TestClient`.
* [Coverage.py](https://github.com/nedbat/coveragepy) - Code coverage measurement.

---

## 🚀 DevOps, Deployment & Docker
*Running FastAPI in production environments.*
* [Uvicorn](https://www.uvicorn.org/) - The lightning-fast ASGI server implementation used to run FastAPI.
* [Gunicorn](https://github.com/benoitc/gunicorn) - WSGI/ASGI application server container manager.
* [FastAPI Docker Official Images](https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker) - Standard production-ready Docker images by Tiangolo.
* [Granian](https://github.com/emmett-framework/granian) - A Rust-powered HTTP/1, HTTP/2, websockets ASGI server.

---

## 🧰 Extensions, Utilities & Middleware
*Handy productivity boosters and middleware extensions.*
* [FastAPI Mail](https://github.com/sabuhish/fastapi-mail) - Light mail system for sending emails and attachments.
* [FastAPI CORS Middleware](https://fastapi.tiangolo.com/tutorial/cors/) - Native Cross-Origin Resource Sharing handling.
* [FastAPI Pagination](https://github.com/uriyyo/fastapi-pagination) - Simple and reusable pagination for FastAPI.

---

## 📚 Community, Blogs & Tutorials
*Where to learn and stay updated.*
* [TestDriven.io FastAPI Courses](https://testdriven.io/) - Exceptional deep-dive tutorials on FastAPI development.
* [FastAPI Official Blog](https://fastapi.tiangolo.com/blog/) - Updates straight from the creator.
* [Python bytes Podcast](https://pythonbytes.fm/) - Regular updates on FastAPI developments.

---

## 🤝 Contributing

Contributions are always welcome! Please read the [contributing guide](CONTRIBUTING.md) to learn about how to propose changes, add tools, or fix broken links.

---

## 📜 License

This project is licensed under the terms of the [MIT License](LICENSE).
