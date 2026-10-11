# RaceDay API

A RESTful Web API for managing road running, walking, and cycling events in South Africa. Built with **ASP.NET Core 8.0** and **Entity Framework Core** using a **Code-First** approach.

---

## 📋 Project Overview

The RaceDay API is the backend for the RaceDay event management system. It allows:

- **Participants** to browse events, enrol in race categories, and view their personal results.
- **Organisers** to create and manage events, categories, and record participant results.

The API uses **JWT-based authentication** with **role-based access control** to secure endpoints.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| ASP.NET Core 8.0 | Web API framework |
| Entity Framework Core 8.0 | ORM (Code-First) |
| SQL Server (LocalDB) | Database |
| JWT (JSON Web Tokens) | Authentication |
| BCrypt.Net-Next | Password hashing |
| Swagger / Swashbuckle | API documentation |
| xUnit | Unit testing |
| GitHub Actions | CI/CD pipeline |

---

## 🚀 Setup Instructions

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or newer
- [Visual Studio 2022](https://visualstudio.microsoft.com/) (with ASP.NET workload)
- SQL Server LocalDB (installed with Visual Studio)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/PROG6212-RaceDay-API.git
cd PROG6212-RaceDay-API
