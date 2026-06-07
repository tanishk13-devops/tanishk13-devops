# Tanishk Jaiswal

```
  Software Development Engineer (SDE) | Backend & Full-Stack Systems
  Focusing on Clean Architecture, Test-Driven Development (TDD), and Automation
```

---

### ⚡ Recruiter Snapshot

*   **Current Status**: Active job seeker looking for immediate opportunities.
*   **Target Roles**: Software Development Engineer (SDE), Backend Developer, Python/Full-Stack Developer, QA Automation Engineer, Data Analyst.
*   **Core Technologies**: Python (FastAPI/Django), JavaScript/TypeScript (React.js, Node.js), C# (.NET Core), SQL (PostgreSQL, MSSQL).
*   **DevOps & Infrastructure**: Docker, GitHub Actions, Linux.
*   **Testing & Quality Assurance**: PyTest, Playwright, Jest, API and Integration testing.
*   **Availability**: Immediate (Remote or On-Site).
*   **Location**: India (Open to relocation).
*   **Work Interest**: Full-Time roles.

---

### 🔭 Featured Engineering Projects

### 1. AI Resume Analyzer (Python / NLP)
*An intelligent AI-powered resume parser and analyzer extracting skills, experience, and scoring job descriptions fitment.*

🔗 **Live Demo**: [https://ai-resume-analyzer.streamlit.app](#)
📂 **Repository**: [https://github.com/tanishk13-devops/ai-resume-analyzer](https://github.com/tanishk13-devops/ai-resume-analyzer)

*   **Tech Stack**: Python, LLM API, Pydantic, Streamlit, PDFPlumber, PyTest, GitHub Actions.
*   **Key Engineering Achievements**:
    *   Parsed complex multi-column resumes with 95% accuracy using PDFPlumber and custom regex filters.
    *   Integrated a structured OpenAI JSON schema output validator using Pydantic to prevent LLM schema drift.
    *   Reduced API token costs by 40% through local pre-filtering and system prompt token optimization.
    *   Built an automated regression suite in PyTest running in GitHub Actions to test parsing accuracy across 20+ template resumes.
*   **Architecture Highlights**:
    *   **Database**: Local session state and server cache.
    *   **API Design**: Streamlit frontend interacting with async Python handlers.
    *   **Authentication**: Key-based rate-limiting for user queries.
    *   **Deployment Strategy**: Hosted on Streamlit Cloud with automatic SSL configuration.
*   **Testing Strategy**:
    *   **Unit Testing**: Isolated module testing of business logic, parsing regexes, and file loaders using PyTest.
    *   **Integration Testing**: Validates the integration between pdf parsing output formats and LLM input payloads.
    *   **E2E Testing**: Complete workflow validation testing file upload, parsing, processing, and rendering output logs.
*   **Business Impact**:
    *   **Performance**: Extraction time reduced by 75% compared to manual copy-paste.
    *   **Automation**: Reduced operational overhead by automating data validation using Pydantic, dropping bad schemas by 100% before API processing.
    *   **User Benefits**: Resume grading scores generated in under 3 seconds.

---

### 2. Retail Analytic App (React / Node.js)
*A premium Sales Analytics & Predictive Forecasting Dashboard built to serve Indian Retail Products, helping vendors manage inventory and analyze trends.*

🔗 **Live Demo**: [https://retail-analytic-app.netlify.app](#)
📂 **Repository**: [https://github.com/tanishk13-devops/retail-analytic-app](https://github.com/tanishk13-devops/retail-analytic-app)

*   **Tech Stack**: React.js, Node.js, Express, MongoDB, Tailwind CSS, Chart.js, Jest.
*   **Key Engineering Achievements**:
    *   Developed interactive charts and data tables rendering 10k+ transaction rows smoothly with lazy loading and server-side pagination.
    *   Built a predictive sales forecasting module using historical rolling averages and regression formulas.
    *   Designed RESTful API endpoints in Express with structured inputs validation using Joi schemas.
    *   Set up a responsive dashboard utilizing Tailwind CSS, maintaining accessibility (Lighthouse score >90) across mobile and desktop.
*   **Architecture Highlights**:
    *   **Database**: MongoDB Atlas with optimized aggregation pipelines for fast queries.
    *   **API Design**: RESTful MVC API pattern, structured with CORS policies and rate-limiting middleware.
    *   **Authentication**: Secure token-based session management.
    *   **Deployment Strategy**: React frontend deployed on Netlify (CDN cached); Backend Web API containerized and hosted on Render.
*   **Testing Strategy**:
    *   **Unit Testing**: Core business helpers and state reducers tested with Jest and React Testing Library.
    *   **Integration Testing**: Database queries and routes validated with Supertest against local Mongo instances.
    *   **E2E Testing**: Tested critical customer checkout and dashboard filters utilizing automated browser scripts.
*   **Business Impact**:
    *   **Performance**: Page load speed increased by 30% via route-level code splitting and lazy loading components.
    *   **Automation**: Real-time alerts for low stock levels automated, removing the need for daily manual audits.
    *   **User Benefits**: Vendors optimize stock procurement, cutting storage inventory costs by 20%.

---

### 3. Ziggy Delivering Happiness (.NET Core / SQL)
*A backend web API modeling complex delivery routing, kitchen queue updates, and driver dispatch workflows.*

🔗 **Live Demo**: [https://ziggy-delivery-api.up.railwayapp.com](#)
📂 **Repository**: [https://github.com/tanishk13-devops/ziggy-delivering-happiness](https://github.com/tanishk13-devops/ziggy-delivering-happiness)

*   **Tech Stack**: C#, .NET Core Web API, Entity Framework Core, SQL Server, xUnit, Docker.
*   **Key Engineering Achievements**:
    *   Modeled delivery dispatcher queuing systems using asynchronous C# Task Parallel Library (TPL).
    *   Implemented Entity Framework Core with Repository Pattern, securing high-performance transactional isolation during driver dispatch actions.
    *   Engineered unit and integration tests using xUnit, mocking DB contexts to achieve 85% test coverage.
    *   Containerized the .NET runtime environment in a multi-stage Dockerfile, decreasing package size for rapid cloud deployment.
*   **Architecture Highlights**:
    *   **Database**: MS SQL Server containing transactional schemas with relations and constraints.
    *   **API Design**: Clean ASP.NET Controller-based APIs with custom validation filters and standardized HTTP status returns.
    *   **Authentication**: Stateless JWT Authentication with role definitions (Customer, Kitchen Staff, Driver).
    *   **Deployment Strategy**: Automated builds deployed to AWS ECS instances.
*   **Testing Strategy**:
    *   **Unit Testing**: Core business logic and helper functions isolated and tested via xUnit.
    *   **Integration Testing**: API controllers and database query paths validated with InMemory DB providers.
    *   **E2E Testing**: Complete order creation to driver delivery flow simulated and asserted.
*   **Business Impact**:
    *   **Performance**: Parallel driver dispatch queuing processes requests 35% faster.
    *   **Automation**: Real-time delivery state updates automated via background workers.
    *   **User Benefits**: Stable, multi-role API with zero race conditions on order allocation.

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
*   **DevOps & CI/CD**: Docker, GitHub Actions, Linux administration.
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
