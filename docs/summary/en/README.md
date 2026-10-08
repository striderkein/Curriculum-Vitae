# Curriculum Vitae (Summary)

[Full version (English)](https://striderkein.github.io/Curriculum-Vitae/en) | [日本語（要約版）](https://striderkein.github.io/Curriculum-Vitae/summary)

## Basic Information

| key               | value                                      |
| ----------------- | ------------------------------------------ |
| Name              | Shirow Ozawa                               |
| Date of Birth     | 1972-10-10                                 |
| Residence         | Tokyo, Japan                               |
| Highest Education | Faculty of Education, Yamanashi University |

---

## Career Summary

Full-stack engineer with 15 years in software development, focused on TypeScript / React front ends and Node.js / Java / Ruby back ends. Currently development team leader on a logistics DX SaaS product, where AI-driven development with Claude Code is part of the daily workflow.

- **AI-driven development as a daily practice:** works in Claude Code every day and introduced it to the team, from parallel implementation to automated code review and self-healing E2E tests.
- **Leading a 4-person team** on "LogiGo," a logistics DX SaaS (TypeScript + React / NestJS + Prisma / PostgreSQL / AWS), owning everything except infrastructure configuration.
- **Built an E2E / VRT test platform from scratch** with Playwright and led the full migration, including nightly runs, automatic issue filing on failure with AI-driven auto-fixes, and E2E coverage measurement.
- **Drove measurable business results:** +12% CVR from conversion-oriented UI work, +10% new customer inflow and +5-6% SEO score from content platform improvements.
- **Delivered products at scale:** PWA for a retail electricity provider with 500,000 users, WebRTC video lesson platform with 40,000 unique users.
- **Modernizes legacy code bases** into maintainable front ends, with unit testing, CI/CD, and developer tooling as a standing part of the work.
- **Broad domain background:** logistics, energy, finance, EC, public sector, and telecom, across both product companies and contract development.

---

## AI-Driven Development (Claude Code)

Claude Code is my primary development environment, used daily for implementation, refactoring, review, and operational work. I introduced it to my current team and built the practices and tooling around it.

- **Parallel development:** run multiple Claude Code sessions against separate git worktrees so several features and fixes progress at once; my own work shifts toward specification, decomposition, and review.
- **Custom skills as team assets:** author reusable Claude Code skills that encode the team's workflows — PR creation, test-first bug fixing with RED / GREEN commits, review-comment resolution, and specification Q&A grounded in the code base — so any member can repeat the same process.
- **Agents in CI:** combine Claude Code with GitHub Actions for automated code review, review requests, two-way sync with the ticket management system, and notifications.
- **Self-healing tests:** E2E failures automatically file issues and trigger AI-driven fixes, keeping the nightly suite actionable rather than noisy.
- **Quality guardrails:** AI output is treated as input to review, not as a shortcut — tests are written to fail first, lint / VRT gates run in CI, and every change goes through human review.

---

## Core Skills

- Front-end development and design with JavaScript / TypeScript + React.js or Vue.js
- Refactoring legacy code into modern front-end solutions
- Establishing front-end foundations (test environments, initial framework setup, CI/CD)
- Maintainable, reusable code centered on unit testing
- Server-side development with NestJS, Ruby on Rails, express, and Spring Boot
- AI-driven development with Claude Code: parallel sessions, custom skills, and development process automation
- Agile / Scrum practice; team leadership, code review, guidance, and training

---

## Technology Stack

### Language

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
  <img alt="Ruby" src="https://img.shields.io/badge/-Ruby-CC342D?style=flat-square&logo=Ruby&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white" />
  <img alt="Swift" src="https://img.shields.io/badge/-Swift-000096?style=flat-square&logo=Swift&logoColor=white" />
  <img alt="ObjectiveC" src="https://img.shields.io/badge/-ObjectiveC-009600?style=flat-square&logo=ObjectiveC&logoColor=white" />
  <img alt="PHP" src="https://img.shields.io/badge/-PHP-730000?style=flat-square&logo=PHP&logoColor=white" />
</p>

### Frameworks and Others

<p>
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="Vue" src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white" />
  <img alt="Ruby-on-Rails" src="https://img.shields.io/badge/-Rails-CC0000?style=flat-square&logo=Ruby-on-Rails&logoColor=white" />
  <img alt="Apollo" src="https://img.shields.io/badge/-Apollo%20GraphQL-311C87?style=flat-square&logo=apollo-graphql&logoColor=white" />
  <img alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img alt="Firebase" src="https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=white" />
  <img alt="Gatsby" src="https://img.shields.io/badge/-Gatsby-663399?style=flat-square&logo=Gatsby&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=Vite&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="mongoDB" src="https://img.shields.io/badge/-mongoDB-03684A?style=flat-square&logo=mongoDB&logoColor=white" />
</p>

---

## Work Experience

### SImount Inc. (2026/01 - Present) — Development Team Leader

Full-stack development of "LogiGo," a logistics DX SaaS platform. Responsible for all aspects of development except infrastructure configuration: new features, performance optimization, API design, and test infrastructure. Team of 4. Introduced Claude Code to the team and established the parallel development method the team now works with.

**Stack:** TypeScript + React / NestJS + Prisma / PostgreSQL / AWS / Playwright / GitHub Actions

- Led feature development for billing and payment: ancillary charge entry and aggregation, report / CSV export, consumption tax support (tax category, tax-inclusive/exclusive pricing, rounding), design and implementation of closing dates as a first-class feature (day-level closing dates, accounting months, closing-date-based search and aggregation), and monthly report improvements.
- Delivered extensive features for the dispatch planning board: forced assignment / swap / unassignment, vehicle inspection due-date alerts, enhanced search, and drag-and-drop defect fixes.
- Expanded master data management (vehicles, sites, customers; customer-site linking UI; CSV import for each master) with the underlying data model improvements.
- Expanded Excel template-based report output, including delivery request forms, dispatch result reports, and vehicle number notices matching the company-wide format of a major logistics company.
- Built the E2E / VRT test platform with Playwright from scratch and led the full migration: visual regression testing, nightly automated runs, automatic issue filing on E2E failure with AI-driven auto-fixes, and E2E coverage measurement.
- Automated the development process with Claude Code skills and GitHub Actions: code review, review requests, two-way sync with the ticket management system, and notifications; ran multiple Claude Code sessions on git worktrees to develop features in parallel.
- Improved CI/CD and performance: faster runners for cost and time savings, migration drift detection, VRT stabilization, API response compression, monitoring alarms as IaC, better observability with Sentry, and a permanent fix for a production incident caused by expired authentication tokens.

### Server-Free Corporation (2024/02 - 2025/11) — Detailed Design, Implementation

Business system development for a major infrastructure company, covering backend API development, front-end modification, and cloud deployment. Two-person teams.

**Stack:** React + TypeScript / Spring Boot / MySQL / Azure

- Developed a data integration batch and a PDF generation REST API with Spring Boot.
- Modified the front end of a business system built with jQuery.
- Deployed the Spring Boot API to Azure App Service.
- Reason for leaving: personal reasons.

### Zehitomo Co., Ltd. (2022/08 - 2023/08) — Detailed Design, Implementation, Testing, Code Review

Development of a matching service between small and medium-sized businesses and individual customers. Led design and implementation of features that improve user convenience, and led front-end improvement activities, including responsive design based on experience from smartphone app development. Scrum team of 3-5.

**Stack:** TypeScript + Next.js / Redux, AngularJS / express, MongoDB / AWS ECS, S3 / WordPress

- Implemented conversion-oriented UI, **improving CVR by 12%**.
- Developed APIs with express and MongoDB on AWS ECS and S3.
- Improved low-quality blog content, **raising the SEO score by 5-6%**, and built new content that **increased new customer inflow by 10%**.
- Reason for leaving: voluntary retirement due to the company's declining performance.

### 2nd Community Co., Ltd. (2022/01 - 2022/07) — Lead Engineer, Video Streaming

Development of a WebRTC web application for online lessons, providing chat, video meetings, and drawing, on a site with 40,000 unique users. Two-person team.

**Stack:** Vue / Nuxt.js / Ruby on Rails / Docker / Amazon S3

- Implemented the video meeting screen, including core functionality and responsive design.
- Added file attachment and emoji support to the chat feature.
- Implemented Undo / Redo for the drawing feature using localStorage.
- Reason for leaving: the company suddenly required all employees to keep cameras on at all times during working hours.

### GoodWorks Co., Ltd. (2021/02 - 2021/12) — Detailed Design, Implementation, Code Review, OJT

SES. Four projects, in teams of 1 to 5.

- **Video streaming web app (2021/05 - 2021/11):** front-end and batch design and implementation; specification changes and unit / integration testing for the billing report batch used in usage settlement; technical investigation for unicast delivery; built and deployed a web app that authenticates movie ticket numbers for home viewing.
- **Log collection batch for a public transportation smartphone app (2021/10):** solo development with Python, AWS Batch, and AWS SAM.
- **Disaster information management system for government agencies (2021/04):** front end with Vue + Amplify, Apollo Client, GraphQL, and AWS CodeCommit.
- **IoT device coordination system (2021/02 - 2021/03):** entrance / exit management for construction workers for COVID-19 prevention; front end with Vue3 / Vue, back end with express.
- Reason for leaving: wanted to work at a company doing in-house product development.

### System I Co., Ltd. (2019/12 - 2020/12) — Requirement Definition through Integration Testing

Development of a PWA for a retail electricity provider's contract users, **500,000 users**. Team of 5-10.

- Prototyped the user authentication platform with Cognito.
- Developed a push notification creation batch with TypeScript.
- Dockerized an existing Node.js application.
- Reason for leaving: workplace harassment.

### Mulodo Co., Ltd. (2019/03 - 2019/12) — Requirement Definition through Integration Testing

Outsourced development. Teams of 5-10 and solo work.

- Customization and maintenance of an EC platform for an EC site operator, with PHP / Laravel; also handled inventory management tooling.
- Designed and built a P2P chat app: authentication platform on Firebase (Realtime Database, Authentication), front end with React Native for Web, iOS, and Android.
- Reason for leaving: the company went bankrupt.

### Koei System Co., Ltd. (2017/10 - 2019/02) — High-level Design through Testing

Development and service provision of a dispatch system. Solo development across four projects.

- Built a RESTful PDF generation web API in C#, generating PDFs from database records on POST.
- Built a web API for interfacing with Oracle.
- Developed the dispatch system front end: an interactive dispatch table for tank trucks with D3.js.
- Built a web app visualizing server operation records, with a batch converting log files into Google Charts JSON; deployed and operated an HTTP proxy on AWS EC2.

### Delta Wing Co., Ltd. (2013/03 - 2017/09) — Design, Implementation, Testing

SES. 13 projects in waterfall and agile teams of 1-6, mainly in finance, public sector, telecom, and content.

| Period            | Project                                      | Technologies                |
| ----------------- | -------------------------------------------- | --------------------------- |
| 2017/07 - 2017/09 | International bank account information system | Java, HiRDB                |
| 2017/02 - 2017/06 | EC web app and iOS app maintenance, content provider app | Objective-C, PHP / Smarty, MySQL |
| 2016/12 - 2017/01 | 4K set-top box for satellite broadcasting     | VanillaJS                  |
| 2016/10 - 2016/11 | Mobile base station management system (basic design of disaster response features) | — |
| 2016/04 - 2016/09 | Report management system for a bank (PDF and SOAP API DLLs) | C++             |
| 2015/10 - 2016/03 | Maritime defense ship position system, GIS server product selection | JavaScript / D3.js, Java |
| 2015/03 - 2015/09 | BI operations for content business; customer management tool for insurance agents | Web app over mainframe data |
| 2014/08 - 2015/02 | Membership site renewal for Disney Japan (RESTful API) | Java / Apache Wink, jQuery |
| 2013/10 - 2014/07 | Parcel delivery support system; credit card merchant management system | Batch, stored procedures, JSP |
| 2013/03 - 2013/11 | Corporate internal SNS iOS app; iOS port of a pedestrian navigation app | Objective-C |

### Earlier Career (1995 - 2013)

| Period            | Company / Role                                | Summary                                                          |
| ----------------- | --------------------------------------------- | ---------------------------------------------------------------- |
| 2012/10 - 2013/02 | Pleasant Co., Ltd.                            | Middleware for financial institutions; printing and process launch DLLs for a bank merger (team of 3) |
| 2011/10 - 2012/03 | Frontier Co., Ltd. (internal SE)              | Migrated a C# LAN application for logistics material management and ordering to a web app (Java, JSP, MSSQL) |
| 2010/04 - 2011/03 | Public servant                                | Elementary school teacher                                        |
| 2007/11 - 2009/04 | Adecco Co., Ltd.                              | B Flets salesperson                                              |
| 2003/02 - 2005/02 | Yamato Transport Co., Ltd.                    | Sales driver                                                     |
| 2002/07 - 2003/01 | Number Four Co., Ltd.                         | Contract development, solo: IC card automatic login (Visual C++), image extraction tool for real estate agents (VB6), mobile bulletin board CGI (Perl, HDML, cHTML) |
| 1995/04 - 2001/03 | Public servant                                | Elementary school teacher                                        |

---

## Extracurricular Activities

- **OSS and personal development:** [backlog-tamer](https://github.com/striderkein/backlog-tamer) (CLI tool), and pull requests to OSS including MDN documentation translation.
