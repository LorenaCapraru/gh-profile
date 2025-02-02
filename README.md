# GitHub Commits Tracker

GitHub Commits Tracker is a web application that allows you to track the commits of graduates from a specific cohort. It is built with Next.js, Tailwind CSS, Prisma.
The application's data is stored in a Prisma database with a single table for graduates.
<img width="1000" alt="Screenshot 2023-10-25 at 01 36 16" src="https://github.com/LorenaCapraru/gh-profile/assets/108892538/a69af422-6c72-4fff-ad54-a1093b7b8101">


## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)


## Features

- View a list of graduates from a specific cohort.
- Track the GitHub commits of each graduate.
- View graduate details including their GitHub username, avatar, LinkedIn profile, and role.
- Easily filter and search for specific graduates.

## Tech Stack

- **Next.js**: A React framework for building web applications.
- **Tailwind CSS**: A utility-first CSS framework for building stylish and responsive user interfaces.
- **Prisma**: A modern database toolkit that simplifies database access in Node.js.
- **RESTful API**: Provides endpoints to access and manipulate graduate data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- A PostgreSQL database set up for Prisma (update your database connection details in `prisma/schema.prisma`).
- GitHub API credentials if you want to use the GitHub Commits feature.

## Getting Started

1. Clone the repository:

```bash
  git clone https://github.com/yourusername/gh-profile.git
```

2. Navigate to the project directory:
```bash
   cd gh-profile
```
3. Install the project dependencies:
```bash
  npm install
```
4. Apply database migrations:
```bash
  npx prisma migrate dev
```
5. Start the development server:
```bash
  npm run dev
```
7. Visit http://localhost:3000 in your web browser.

## Usage
- Visit the application in your browser.
- Use the search and filter options to find specific graduates by cohort or name.
- Click on a graduate to view their GitHub commits and details.


Happy tracking! 🚀
