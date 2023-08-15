# Secrets-Authentication

### [Live Site](https://secrets-app-9ox9.onrender.com/)

![SecretKeeper](https://github.com/ehasan8115/Secrets-Authentication/blob/master/public/images/secrets-home.png?raw=true)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Used](#technology-used)
- [Usage](#usage)

## Project Overview

The SecretKeeper web application provides a platform for users to anonymously share secrets, explore secrets shared by others, and engage in a community-driven experience. Users can authenticate using their Google account or create a local account. Once logged in, they can submit their secrets, view secrets from other users, and enjoy a sense of community.

## Features

- **User Authentication**:
  - Users can register and log in using their Google account or local credentials.
  - Google OAuth 2.0 is implemented for seamless authentication using Google accounts.
  - Passport.js is used for handling user authentication and sessions.

- **Secret Submission and Viewing**:
  - Authenticated users can submit their secrets through a dedicated submission page.
  - Submitted secrets are stored in the database and displayed on the "Secrets" page.
  - Users can explore secrets shared by other users in an anonymous manner.

- **Community Interaction**:
  - Users can view a collection of secrets shared by the community on the "Secrets" page.
  - The application encourages a sense of shared experience by enabling users to engage with secrets submitted by others.

- **User Profile**:
  - Each user has a profile that displays their submitted secrets.
  - Users can manage their submitted secrets and explore other user profiles.

## Technology Used

- **Frontend**:
  - HTML, CSS, Bootstrap: Building the user interface and responsive design.
  - EJS (Embedded JavaScript): Templating engine for dynamic content rendering.
  
- **Backend**:
  - Node.js: Server-side JavaScript runtime environment.
  - Express.js: Web application framework for routing and middleware.
  - MongoDB: NoSQL database for storing user data and secrets.

- **Authentication**:
  - Passport.js: Authentication middleware for user authentication and sessions.
  - Google OAuth 2.0: Enabling Google account authentication.

- **Deployment**:
  - Render: Cloud platform used for deploying and hosting the web application.

## Usage

- Register or log in using your Google account or local credentials.
- Submit your secrets on the "Submit a Secret" page.
- Explore secrets shared by other users on the "Secrets" page.
- Log out when you're done by clicking the "Log Out" button.
