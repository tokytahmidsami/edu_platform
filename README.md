# Hadith Narrator Database

A modern, scalable, and research-oriented platform for exploring, analyzing, and studying the narrators of Hadith.

> **Project Status:** 🚧 Under Active Development

---

## Overview

The Hadith Narrator Database aims to provide a comprehensive digital resource for the science of **ʿIlm al-Rijāl (علم الرجال)** by organizing information about Hadith narrators in a structured and searchable format.

The long-term goal is to build a platform that supports students, researchers, and scholars by combining classical biographical works with modern software engineering practices.

---

## Objectives

* Build a comprehensive database of Hadith narrators.
* Store narrator biographies and scholarly evaluations.
* Model relationships between narrators and teachers/students.
* Support advanced search and filtering.
* Enable chain (Isnād) analysis.
* Provide a scalable API for future integrations.
* Maintain a clean, extensible architecture suitable for long-term development.

---

## Planned Features

### Narrator Management

* Narrator profiles
* Alternate names (kunya, laqab, nisbah)
* Birth and death information
* Places
* Teachers
* Students
* Reliability gradings
* Biographical notes
* References from classical works

### Search

* Full-text search
* Advanced filtering
* Search by narrator
* Search by kunya
* Search by teacher/student
* Search by reliability

### Chain Analysis

* Narrator relationship visualization
* Teacher–student graph
* Isnād traversal
* Connectivity analysis

### API

* REST API
* Authentication
* Authorization
* Pagination
* Filtering
* Versioning

---

## Project Structure

```text
.
├── assets/
├── backend/
├── database/
├── docs/
├── frontend/
├── .github/
├── .vscode/
├── README.md
└── package.json
```

### Directory Overview

| Directory   | Purpose                                                   |
| ----------- | --------------------------------------------------------- |
| `frontend/` | React frontend application                                |
| `backend/`  | NestJS backend API                                        |
| `database/` | Database schema, migrations, seeds, and related resources |
| `docs/`     | Project documentation                                     |
| `assets/`   | Images, logos, diagrams, and other static assets          |
| `.github/`  | GitHub workflows and automation                           |
| `.vscode/`  | Shared VS Code workspace configuration                    |

---

## Planned Technology Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS

### Backend

* NestJS
* TypeScript

### Database

* PostgreSQL
* Prisma ORM

### Development

* Git
* GitHub
* ESLint
* Prettier
* Docker (planned)

---

## Development Philosophy

This project emphasizes:

* Clean Architecture
* SOLID principles
* Type safety
* Modular design
* Scalable codebase
* Maintainable database design
* Thorough documentation
* Incremental development

The objective is not merely to build an application, but to establish a maintainable software project that can continue to evolve over time.

---

## Documentation

Project documentation will be maintained in the `docs/` directory.

Planned documentation includes:

* Requirements
* System architecture
* Database design
* API specification
* Development guide

---

## Roadmap

* [x] Initialize repository
* [x] Establish project structure
* [ ] Configure npm workspaces
* [ ] Scaffold frontend
* [ ] Scaffold backend
* [ ] Configure PostgreSQL
* [ ] Configure Prisma
* [ ] Design database schema
* [ ] Implement authentication
* [ ] Develop REST API
* [ ] Build frontend interface
* [ ] Deployment

---

## Contributing

Contribution guidelines will be added as the project matures.

---

## License

This project is licensed under the terms specified in the `LICENSE` file.

---

## Acknowledgements

This project is inspired by the rich scholarly tradition of Islamic Hadith studies and seeks to complement that tradition with modern software engineering practices.
