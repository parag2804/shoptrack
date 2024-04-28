# ShopTrack

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction
ShopTrack is an innovative e-commerce price tracking application designed to help consumers make informed purchasing decisions by providing real-time notifications on price drops and stock availability.

## Features
- Real-time price tracking of online products.
- Instant alerts on price drops and stock restocks.
- User-friendly interface for easy navigation and interaction.
- Historical price trend analysis for smart purchasing.

## Technology Stack
- Frontend: Next.js, Tailwind CSS, Headless UI
- Backend: Node.js, MongoDB with Mongoose
- Automation: cron-jobs.org for scheduled tasks
- Deployment: Vercel for CI/CD and hosting

## Getting Started
To get a local copy up and running, follow these simple steps.

**##Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/parag2804/shoptrack.git
cd shoptrack
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from [BrightData](https://brightdata.com/), [MongoDB](https://www.mongodb.com/), and [Node Mailer](https://nodemailer.com/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
