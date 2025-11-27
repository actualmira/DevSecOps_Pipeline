# About the Target Application

## OWASP Juice Shop

This project uses OWASP Juice Shop v19.1.1 as the target application for security testing and pipeline development.

### What It Is

OWASP Juice Shop is an intentionally vulnerable web application developed by the OWASP Foundation for security training and testing. It contains real vulnerabilities from the OWASP Top 10 and serves as a practice environment for security professionals worldwide.

The application represents a modern e-commerce platform with typical features—user authentication, product catalog, shopping cart, and reviews—all implemented with deliberate security flaws for educational purposes.

### Technical Specifications

**Application Details:**
- **Version:** 19.1.1
- **License:** MIT License
- **Copyright:** © 2014-2026 Björn Kimminich & OWASP Juice Shop contributors

**Technology Stack:**
- **Backend Framework:** Express.js 4.21.0
- **Runtime:** Node.js
- **Frontend Framework:** Angular
- **Language:** TypeScript
- **Database:** SQLite with Sequelize ORM
- **Containerization:** Docker

**Source Repository:** https://github.com/juice-shop/juice-shop  
**Official Site:** https://owasp-juice.shop

### Project Attribution

**From OWASP Juice Shop:**

All application source code, including:
- Frontend implementation (`frontend/`)
- API routes and endpoints (`routes/`)
- Database models and schemas (`models/`)
- Business logic and utilities (`lib/`)
- Configuration files and dependencies
- The intentional vulnerabilities being tested

**My Contribution:**

Security testing infrastructure and analysis:
- All GitHub Actions workflows and CI/CD configuration
- Security scanning integration (Snyk, OWASP ZAP)
- Manual vulnerability testing and documentation
- Security analysis and findings reports
- Deployment automation and security gates
- Project documentation and methodology

### Scope Clarification

This project demonstrates security pipeline implementation and DevSecOps practices using Juice Shop as the test target. The application code serves as the vulnerable system being analyzed; the security testing infrastructure, methodology, and analysis represent the original work being showcased.

The choice to use an existing vulnerable application rather than building one allows focus on what matters for DevSecOps: integrating security tools, automating testing, establishing security gates, and demonstrating professional security analysis.

### Acknowledgment

This project wouldn't be possible without the OWASP Juice Shop team's work in creating and maintaining a comprehensive, modern vulnerable application for the security community.

**Project Maintainer:** Björn Kimminich  
**Contributors:** OWASP Juice Shop community  
**Documentation:** https://pwning.owasp-juice.shop

---

*Using OWASP Juice Shop v19.1.1 under MIT License. All security pipeline implementation and documentation are original work.*
