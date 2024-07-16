
# Next.js Dashboard Project

This project is a Next.js dashboard application connected to a Vercel/PostgreSQL database. It includes features like user authentication, data visualization, and CRUD operations for invoices and customers.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Seeding the Database](#seeding-the-database)
- [Technologies Used](#technologies-used)

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- PostgreSQL database set up
- Vercel account (optional for deployment)

### Installation

1. Clone the repository:

    \`\`\`sh
    git clone https://github.com/dlinh31/nextjs-dashboard.git
    cd nextjs-dashboard
    \`\`\`

2. Install the dependencies:

    \`\`\`sh
    npm install
    \`\`\`

3. Set up environment variables:

    Create a \`.env\` file in the root of your project and add the following variables:

    \`\`\`env
    POSTGRES_URL=your_vercel_postgres_connection_string
    \`\`\`

### Running the Application

To run the application in development mode, use the following command:

\`\`\`sh
npm run dev
\`\`\`

This will start the development server on \`http://localhost:3000\`.

To build the application for production, use:

\`\`\`sh
npm run build
\`\`\`

To start the production server, use:

\`\`\`sh
npm run start
\`\`\`

### Seeding the Database

To seed the database with initial data, you can run the seed script:

1. Ensure your PostgreSQL database is running and the connection string is set in the \`.env\` file.

2. Run the seed script:

    \`\`\`sh
    npm run seed
    \`\`\`

This will populate your database with sample data for users, invoices, customers, and revenue.


### Logging in
You can log in with the credentials stored inside placeholder-data.js, or add your own credentials



### Technologies Used

- **Next.js**: React framework for server-side rendering and static site generation.
- **React**: JavaScript library for building user interfaces.
- **PostgreSQL**: Relational database for data storage.
- **Vercel**: Hosting and deployment platform.
- **bcrypt**: Library for hashing passwords.


