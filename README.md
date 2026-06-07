# Tanishk Jaiswal

```
  Software Development Engineer (SDE) | Backend & Full-Stack Systems
  Focusing on Clean Architecture, Test-Driven Development (TDD), and Automation
```

---

### ⚡ Recruiter Snapshot

*   **Current Status**: Active job seeker looking for immediate opportunities.
*   **Target Roles**: Software Development Engineer (SDE), Backend Developer, Python/Full-Stack Developer, QA Automation Engineer.
*   **Core Technologies**: Python (FastAPI, Django), JavaScript/TypeScript (React.js, Node.js), C# (.NET Core), SQL (PostgreSQL, MSSQL).
*   **DevOps & Infrastructure**: Docker, Kubernetes, AWS, GitHub Actions, Linux.
*   **Testing & Quality Assurance**: PyTest, Playwright, Jest, API and Integration testing.
*   **Availability**: Immediate (Remote or On-Site).
*   **Location**: India (Open to relocation).
*   **Work Interest**: Full-Time roles.

---

### 🔭 Featured Engineering Projects

### 1. Telemetry Streamer & Task Orchestrator
*A highly scalable, event-driven backend system built for real-time log ingestion, job queuing, and performance monitoring.*

🔗 **Live Demo**: [https://tanishk-telemetry-demo.up.railwayapp.com](#)
📂 **Repository**: [https://github.com/tanishk13-devops/telemetry-streamer](#)

*   **Tech Stack**: Python, FastAPI, Celery, Redis, PostgreSQL, PyTest, Docker, GitHub Actions.
*   **Key Engineering Achievements**:
    *   Designed an event-driven task processing system utilizing Celery and Redis to handle peak ingestion rates of 1,200 log packets/second without API blocking.
    *   Wrote 50+ PyTest integration tests validating task state transitions, achieving 94% code coverage in CI.
    *   Reduced API response latency by 40% (p95 from 180ms to 108ms) by implementing PostgreSQL indexing and connection pooling.
    *   Optimized containerization with multi-stage Docker builds, shrinking the application image size from 820MB to 160MB.
*   **Architecture Highlights**:
    *   **Database**: PostgreSQL with SQLAlchemy ORM, using Alembic for declarative schema migrations.
    *   **API Design**: RESTful API design using FastAPI, featuring auto-generated OpenAPI documentation, query caching, and response schemas.
    *   **Authentication**: JWT-based stateless authentication with token expiration and blacklisting via Redis.
    *   **Deployment Strategy**: Hosted on Dockerized Railway environments with automatic SSL, scale-to-zero configurations, and Prometheus monitoring.
*   **Testing Strategy**:
    *   **Unit Testing**: Isolated module testing of business logic, utility functions, and custom exception handlers using PyTest.
    *   **Integration Testing**: Database transaction isolation tests using test databases spun up inside Docker containers before each test execution.
    *   **E2E Testing**: Complete workflow testing from HTTP client requests to background job execution and database state assertion.
*   **Business Impact**:
    *   **Performance**: Log streaming processing delays decreased by 60%.
    *   **Automation**: Reduced operational overhead by automating data validation using Pydantic, dropping bad schemas by 100% before database entry.
    *   **User Benefits**: High-availability dashboard loads under 200ms, enhancing data visibility.

---

### 2. Distributed Inventory Management System (.NET Core / React)
*An enterprise-ready Full-Stack application featuring clean separation of concerns and robust transactional data integrity.*

🔗 **Live Demo**: [https://tanishk-inventory-react.netlify.app](#)
📂 **Repository**: [https://github.com/tanishk13-devops/inventory-management](#)

*   **Tech Stack**: C# (.NET Core Web API), Entity Framework Core, MSSQL, React, TypeScript, Tailwind CSS, Jest, xUnit.
*   **Key Engineering Achievements**:
    *   Implemented clean architecture with Repository and Unit of Work design patterns, ensuring domain layer isolation from data access details.
    *   Created a responsive single-page application (SPA) in React and TypeScript with optimized component rendering states.
    *   Designed complex database transactions enforcing ACID compliance during concurrent inventory updates.
    *   Integrated Jest and xUnit testing pipelines running on GitHub Actions to prevent regressions on API controller endpoints.
*   **Architecture Highlights**:
    *   **Database**: Microsoft SQL Server configured with Entity Framework Core code-first migrations.
    *   **API Design**: ASP.NET Core Web API utilizing action filters, custom exception middleware, and standard REST response contracts.
    *   **Authentication**: Cookie-based secure HTTPOnly JWT tokens, mitigating Cross-Site Scripting (XSS) risks.
    *   **Deployment Strategy**: React frontend deployed on Netlify (CDN cached); Backend Web API containerized and hosted on AWS ECS.
*   **Testing Strategy**:
    *   **Unit Testing**: Core domain logic and business rules tested using xUnit (backend) and Jest/React Testing Library (frontend).
    *   **Integration Testing**: Controllers and services validated using InMemory database providers to simulate DB operations.
    *   **E2E Testing**: Critical customer paths (e.g., ordering items, stock checkout) tested with automated Playwright browser scripts.
*   **Business Impact**:
    *   **Performance**: Page load speed increased by 30% via route-level code splitting and lazy loading components.
    *   **Automation**: Real-time alerts for low stock levels automated, removing the need for daily manual audits.
    *   **User Benefits**: Zero inventory sync conflicts reported due to database optimistic concurrency controls.

---

### 3. E2E QA Test Automation Framework & Validator
*A robust, modular automated testing suite simulating user actions, reporting metrics, and validating API structures.*

🔗 **Live Demo**: [https://tanishk-qa-dashboard.github.io](#)
📂 **Repository**: [https://github.com/tanishk13-devops/qa-automation-framework](#)

*   **Tech Stack**: Python, Playwright, pytest-html, Pydantic, Jenkins, GitHub Actions.
*   **Key Engineering Achievements**:
    *   Developed a Page Object Model (POM) testing framework in Playwright, executing parallel tests across Chrome, Firefox, and WebKit.
    *   Created an API schema validator using Pydantic, validating 100% of JSON payloads against expected API structures in under 5ms.
    *   Configured automated CI/CD runs executing regressions on every code pull, generating static HTML reports with screenshot attachments.
    *   Integrated Slack webhook alerts to instantly notify the engineering team of pipeline test failures.
*   **Architecture Highlights**:
    *   **Database**: No database required (stateless execution); results generated as HTML and JSON test logs.
    *   **API Design**: Validates external public microservice endpoints using Python requests library with custom assertions.
    *   **Authentication**: Automated authentication handling by storing browser context states, reducing test login times by 80%.
    *   **Deployment Strategy**: Test pipeline runs as a containerized task inside GitHub Actions, publishing HTML results to GitHub Pages.
*   **Testing Strategy**:
    *   **Unit Testing**: Core helper classes, mock configurations, and API payload parsers are covered.
    *   **Integration Testing**: Checks the pipeline's capability to process API inputs and generate consistent JSON report structures.
    *   **E2E Testing**: Simulates multi-user, multi-browser flows, handling UI elements, network intercepts, and popups.
*   **Business Impact**:
    *   **Performance**: Parallel testing reduced full regression suite runtime from 12 minutes to 2 minutes.
    *   **Automation**: Replaced manual regression testing, saving QA teams approximately 10 hours of manual testing per release cycle.
    *   **User Benefits**: High deployment safety, ensuring zero broken flows reach production.

---

### 🔨 Currently Building & Learning

*   **Active Project**: Microservices event mesh using Kafka and FastAPI for high-throughput stream processing.
*   **Learning Roadmap**:
    *   **Cloud Orchestration**: Kubernetes scaling policies, ingress controllers, and Helm charts.
    *   **Testing Methodology**: Mutation testing in Python (`mutmut`) to evaluate test suite quality.
    *   **System Design**: Designing systems for high availability, fault tolerance, and horizontal scalability.

---

### 🛠️ Technical Capabilities

*   **Programming Languages**: Python, JavaScript, TypeScript, C#, SQL, Bash.
*   **Backend Frameworks**: FastAPI, Node.js, Express.js, Django, ASP.NET Core.
*   **Frontend Technologies**: React.js, HTML5, CSS3, Tailwind CSS.
*   **Databases & Caches**: PostgreSQL, Microsoft SQL Server, MongoDB, Redis.
*   **Cloud Infrastructure**: Amazon Web Services (AWS EC2, S3), Railway, Netlify.
*   **DevOps & CI/CD**: Docker, GitHub Actions, Linux administration, Jenkins.
*   **Testing & Quality Assurance**: PyTest, Playwright, Jest, xUnit, React Testing Library.
*   **AI & Automation**: LangChain, LLM API integration, automated ETL scripting.

---

### 📊 GitHub Diagnostics & Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tanishk13-devops&show_icons=true&theme=tokyonight&hide_border=true" alt="Tanishk's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanishk13-devops&layout=compact&theme=tokyonight&hide_border=true" alt="Tanishk's Top Languages" width="48%" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tanishk13-devops&theme=tokyonight&hide_border=true" alt="Tanishk's GitHub Streak" width="760" />
</div>

---

### 🤝 Open Source Contributions

I actively participate in open-source projects to refine my system-level understanding and collaborate with global engineering teams.

*   **[tanishk13-devops/pr-contributions](#)**: Resolved issue `#204` in a FastAPI utility library to handle edge-case null headers correctly.
*   **Documentation**: Contributed translations and setup scripts for Docker integration guides on various open-source packages.
*   **Bug hunting**: Reported and patched database connection leak issues in a lightweight .NET ORM helper script.

---

### 💡 Engineering Principles

*   **Clean Architecture**: Separation of concerns where the core business rules are isolated from databases, UI, and external frameworks.
*   **SOLID Principles**: Writing modular, extensible, and single-purpose classes to ease code review and scalability.
*   **Test-Driven Development (TDD)**: Writing unit tests before implementation details to ensure functional correctness and predictable API behaviors.
*   **Continuous Integration / Continuous Deployment (CI/CD)**: Automating code linting, security scans, unit tests, and staging deployments on every push.
*   **Performance Optimization**: Database indexing, connection pooling, and payload caching to maximize resource utilization.

---

### 🌐 Connect & Collaborate

*   **LinkedIn**: [tanishk-jaiswal-05a24724a](https://linkedin.com/in/tanishk-jaiswal-05a24724a)
*   **Email**: [nickyjaiswal85@gmail.com](mailto:nickyjaiswal85@gmail.com)
*   **GitHub**: [github.com/tanishk13-devops](https://github.com/tanishk13-devops)
*   **Resume**: [Download Resume (PDF)](#)
