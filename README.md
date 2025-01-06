Technology Stack
Frontend: Next.js, Tailwind CSS, Redux Toolkit, Redux Toolkit Query, Material UI Data Grid
Backend: Node.js with Express, Prisma (PostgreSQL ORM)
Database: PostgreSQL, managed with PgAdmin
Cloud: AWS EC2, AWS RDS, AWS API Gateway, AWS Amplify, AWS S3, AWS Lambda, AWS Cognito
Getting Started
Prerequisites
Ensure you have these tools installed:

Git
Node.js
npm (Node Package Manager)
PostgreSQL 
PgAdmin 
Installation Steps
Clone the repository: git clone [git url] cd project-management

Install dependencies in both client and server: cd client npm i cd .. cd server npm i

Set up the database: npx prisma generate npx prisma migrate dev --name init npm run seed

Configure environment variables:

.env for server settings (PORT, DATABASE_URL)
.env.local for client settings (NEXT_PUBLIC_API_BASE_URL)
Run the project npm run dev
