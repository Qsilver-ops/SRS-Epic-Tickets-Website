# SRS-Epic-Tickets-Website

## Project Overview

EpicTickets is an online platform for purchasing movie tickets. Users can browse showtimes, select their seats through an interactive seating layout, and securely complete their purchases. The platform also supports account management, guest checkout, and integrates with third-party payment systems to ensure a smooth transaction experience. 

Key Features:
- Browse available movie showtimes and theaters
- Interactive visual seating layout for ticket selection
- Account management for registered users, with guest checkout available
- Secure payments with compliance to GDPR and PCI DSS

## Tech Stack

### Frontend:
- **Next.js** (React Framework for server-side rendering and static site generation)
- **JavaScript (ES6+)** / **TypeScript** (for type safety)
- **CSS/SCSS** for styling
- **Tailwind CSS** or **Bootstrap** (optional for utility-first styling)
- **React Context API** or **Redux** for state management
- **React Query** for data fetching and caching

### Backend:
- **Node.js** with **Express.js** or **Next.js API Routes**
- **MongoDB** or **PostgreSQL/MySQL** for database management
- **Prisma** or **Mongoose** as ORM/ODM

### Hosting and Deployment:
- **Google Cloud Platform (GCP)** for cloud hosting
- **Google Cloud Storage** for static asset hosting
- **Google Kubernetes Engine** or **Google App Engine** for app deployment
- **Firebase** (optional for real-time updates)

### Third-Party Integrations:
- **Stripe** or **PayPal** for payment processing
- **TMDb API** for movie information and images
- **SendGrid** or **Mailgun** for email notifications

### Legal Compliance:
- **GDPR** and **PCI DSS** compliance for data protection and secure transactions

### Security:
- **JWT (JSON Web Tokens)** or **OAuth 2.0** for authentication
- **HTTPS** via SSL/TLS certificates

### Performance:
- **Next.js ISR (Incremental Static Regeneration)** for caching
- **Redis** for caching frequently accessed data
- **Cloud CDN** (Content Delivery Network) for static file delivery

### Testing and Monitoring:
- **Jest** for unit and integration testing
- **Cypress** or **Playwright** for end-to-end testing
- **Sentry** or **LogRocket** for error tracking

### Version Control:
- **GitHub** for source control and collaboration
- **GitHub Actions** for CI/CD

Table of Contents

1. INTRODUCTION	
2. Tech Stack
3. Design
4. API	
5. VM
6. Initial Front End

 




