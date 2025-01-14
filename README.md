# ADHD Healthcare Assessment Application

A role-based healthcare application designed to facilitate ADHD assessments. The application provides personalised results powered by AI, video recommendations, documentation, journals, and the ability to share information among professionals. It is built with modern web technologies and ensures the highest standards of security and privacy for its users.

## Features

- **AI-Powered ADHD Assessments**: Get accurate, data-driven results with AI.
- **Role-Based Access Control**:
  - **Healthcare Workers**: Access to patient assessments, medical recommendations, and shared documentation.
  - **Teachers**: Access to patient assessments, medical recommendations, and shared documentation.
  - **Parents**: Access to their child's results, recommendations, and sharing tools.
  - **Students**: Personalised assessment results and learning materials.
- **Recommendations and Resources**: Video suggestions and documentation to aid in ADHD management.
- **Journals**: Maintain detailed records of patient progress.
- **Information Sharing**: Securely share data with authorised professionals.
- **Privacy First**: Implements anonymous database structures for separating personal and medical information.

## Technology Stack

- **Frontend**: React library with Next.js framework.
- **Backend**: ORL Prisma for ORM with PostgreSQL as the database.
- **Security**: 
  - Authentication and authorisation mechanisms.
  - Two databases:
    - One for personal information (anonymous and encrypted).
    - One for medical data.
- **Hosting**: AWS for reliable and scalable deployment.

## Deployment

The application is hosted on **AWS**, ensuring high availability and performance.

