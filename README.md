### Hi, I'm Ever 👋

Full Stack Developer focused on backend architecture, payments, and third-party API integrations. I started coding in 2023 and I'm currently the sole technical owner of a production multi-tenant SaaS platform (e-commerce + influencer marketing).

*🔭 What I work on day to day*
- Backend architecture & API design (NestJS, TypeORM, PostgreSQL)                                                                                                                   - OAuth integrations & webhook verification with e-commerce platforms
- Payment system design (split payments, reconciliation, multi-party payouts)
- Third-party data pipelines (social media analytics, ads platform APIs)
- Production ownership: migrations, incident response, security hardening

*🧩 A few problems I've solved recently* (details generalized — production code is private)
- Diagnosed a webhook signature verification bug caused by a wrong encoding assumption (base64 vs. hex) that had silently rejected valid webhooks for months — fixed it and added a staged-rollout + diagnostic-logging pattern to catch this class of bug earlier
- Designed a payment reconciliation ledger that closes the loop between provide, with idempotent backfill migrations for historical data.
- Built a metrics pipeline over a third-party scraping API, using daily snapshots + delta math to compute accurate monthly totals instead of trusting raw cumulative counters.

*🛠️ Tech I use*

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=po)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

*📫 Reach me:* [LinkedIn](https://www.linkedin.com/in/ever-illesca-20bab8246)
