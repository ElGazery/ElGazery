<h1 align="center">Hi, I'm Kareem Mahmoud Ahmed 👋</h1>

<h3 align="center">Backend Developer | C# • ASP.NET Core • SQL Server</h3>

<p align="center">
I design and build <b>secure, scalable Web APIs</b> using <b>Clean Architecture</b>, <b>CQRS</b> and <b>Domain-Driven Design</b>.<br/>
From authentication and payments to caching and inventory control, I focus on backend systems that are production-ready.
</p>

<p align="center">
  <a href="https://linkedin.com/in/kareem-mahmoud-ahmed/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kareem.mahmoud.ahmed1@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/ElGazery"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## 🚀 About Me

- 🎓 B.Sc. in Computer Science, Nahda University (Beni Suef), GPA 3.6, Very Good with Honors
- 💻 ITI 9-Month Professional Training Program, 2025 to present
- 🏆 Full Stack .NET graduate, Digital Egypt Pioneers Initiative (DEPI)
- 🥇 ECPC Finalist
- 🧩 Freelance developer on Mostaql, delivering backend systems and e-commerce platforms
- 🌱 Passionate about clean, maintainable code, SOLID principles and continuous learning
- 📍 Egypt | Military Status: Exempted

---

## 🛠️ Backend Tech Stack

**Languages & Frameworks**

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Databases & Caching**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Security, Payments & Docs**

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![ASP.NET Identity](https://img.shields.io/badge/ASP.NET%20Identity-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Tools & Cloud**

![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Architecture & Practices**

`Clean Architecture` • `CQRS` • `DDD` • `MediatR` • `Repository & Unit of Work` • `Specification Pattern` • `FluentValidation` • `AutoMapper` • `SOLID` • `UML`

**Frontend (when needed):** HTML • CSS • JavaScript • React • Angular • Bootstrap • Tailwind CSS

---

## 💼 Featured Projects

### 🛒 [Gezo Store: Enterprise E-Commerce Backend API](https://github.com/ElGazery/gezo-store-backend)

A production-grade E-Commerce Web API built with **.NET 10**, following **Clean Architecture**, **CQRS** and **DDD**.

```mermaid
flowchart LR
    Client["Client (Angular / React / Mobile)"] --> API["Gezo.Api"]
    API --> App["Gezo.Application (CQRS + MediatR)"]
    API --> Infra["Gezo.Infrastructure"]
    Infra --> App
    App --> Domain["Gezo.Domain"]
    Infra --> Domain
    Infra --> DB[("SQL Server")]
    Infra --> Cache[("Redis")]
    Infra --> Pay["Stripe"]
```

- 🔐 **Auth:** ASP.NET Core Identity, JWT, refresh token rotation, email verification and password reset
- 🛒 **Basket:** Redis-backed cart, decoupled from relational writes for speed
- 📦 **Orders:** stock validation and deduction inside a Unit of Work transaction to prevent overselling
- 💳 **Payments:** Stripe PaymentIntents and signature-verified webhooks, plus Cash on Delivery
- 🔎 **Catalog:** dynamic filtering, sorting and pagination with the Specification Pattern
- 🛡️ **Reliability:** unified `ApiResponse<T>`, global exception middleware, FluentValidation pipeline
- 📘 **Docs:** Swagger UI with JWT Bearer support

`.NET 10` `C#` `EF Core` `SQL Server` `Redis` `Stripe` `MediatR` `JWT`

### 🏋️ GymApp Backend
RESTful API built with .NET, SQL Server, JWT Authentication, Clean Architecture, Repository Pattern and EF Core.

### 🎮 Gaming & Digital Services Store
Full-stack platform for game top-ups and digital services using React.js, Node.js and MongoDB, deployed on Hostinger.

### ⌚ Luxury Watch Store (Shopify)
Shopify storefront for high-end automatic watches with a custom Liquid theme and modern UI/UX.

### 🎓 Path2Grad
Graduation project, awarded an **Excellent** grade.

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.shion.dev/api?username=Elgazery&theme=dark&hide_border=false&include_all_commits=false&count_private=false"/>
  <img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Elgazery&theme=dark&hide_border=false&layout=compact"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Elgazery&theme=dark&hide_border=false"/>
</p>

---

## 🎯 Currently

- 🔭 Building production-grade APIs with .NET and Clean Architecture
- 📚 Deepening my knowledge of distributed systems, caching and performance
- 🤝 Open to **Backend (.NET) opportunities** and freelance projects

<p align="center">
  <i>"Write code that your future self will thank you for."</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Elgazery&icon=0&color=0"/>
</p>
