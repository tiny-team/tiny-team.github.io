---
title: "Store Dash"
---

# Table of Contents
- [Overview](#overview)
- [User Guide](#user-guide)
- [Developer Guide](#developer-guide)
- [Development history](#development-history)
- [Contact Us](#contact-us)

## Team Contract
To see the team contract for this project, click [here](https://docs.google.com/document/d/1xvAeNWJUuK4aaSVvfV56syp91qet02wTJPp2jsTrT0E/edit?usp=sharing).

## Github Organization
To see the GitHub Organization associated with this project, go to [https://github.com/tiny-team](https://github.com/tiny-team)

# Overview
Aloha Archives is an innovative data portal designed to simplify access to open data in Hawai’i, making it user-friendly, personalized, and visually appealing for citizens of varying technical expertise. Unlike traditional open data platforms, Aloha Archives focuses on tailoring the experience to meet the unique needs of its users through persona-based customization, intuitive navigation, and accessibility for all. It bridges the gap between raw datasets and meaningful insights by providing relevant visualizations, advanced search capabilities, and a seamless user interface.
While other data portals focus primarily on displaying datasets, Aloha Archives transforms the experience into a personalized journey. By prioritizing user personas, providing relevant data visualizations, and ensuring a clean, interactive interface, it democratizes access to data for all Hawai’i citizens, empowering them to make informed decisions, advocate for their communities, and foster innovation.

# User Guide
This section provides a walkthrough of the Aloha Archives user interface and its capabilities.

## For Regular Users
### Landing Page

## For Admin Users
### Admin Page

# Developer Guide
Developers who are interested in running our project locally must have Next.js and PostgreSQL installed. Our tech stack also uses ESLint, Typescript, Bootstrap 5, and React, with deployment via Vercel.

1. Clone the repository to your local computer.
2. Change into the root directory for the project (store-dash) using `cd` command. Then install the necessary third party libraries using `npm install`.
3. Configure PostgreSQL Database by installing PostgreSQL on your local machine.
Then set up your .env.local file in the root of the project with the PostgreSQL connection string: `DATABASE_URL=postgresql://user:password@localhost:5432/dbname` and run database migrations with `npx prisma migrate reset`
4. Run the Project Locally with `npm run dev`
5. Open http://localhost:3000 to view the running local application.

# Development History
## Milestone 1
Milestone 1 aimed to establish a basic outline of our app’s design. Our primary focus was on creating the visual structure and layout to resemble a functional app, without yet implementing full functionality. By setting up the foundational framework, we can efficiently add and refine features in future milestones.

Milestone 1 was managed using [Store Dash GitHub Project Board Milestone 1](https://github.com/orgs/tiny-team/projects/1/views/1):

# Contact Us
Store Dash is designed, maintained, and implemented by [Jared Seto](https://jseto808.github.io/)
