# User List App

## Overview
This is a simple web application built with React and TypeScript that fetches and displays a list of users from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users). The app includes a responsive user interface with loading and error states, styled using CSS. The project is containerized using Docker, managed with Git and GitHub, and includes modern development practices such as linting, testing, and TypeScript for type safety.

### Features
- Fetches user data from the JSONPlaceholder API.
- Displays users in a responsive grid layout.
- Includes loading and error states for better user experience.
- Styled with CSS for a clean and modern look.
- Containerized with Docker for easy setup and deployment.
- Uses TypeScript for type safety.
- Includes ESLint for code linting and React Testing Library for unit tests.
- Implements modern ECMAScript patterns (e.g., optional chaining, nullish coalescing).
- Manages state with a custom `useFetchUsers` hook.

## Prerequisites
- [Node.js](https://nodejs.org/) (version 16 or higher) installed for local development.
- [Docker](https://www.docker.com/products/docker-desktop/) installed to run the app in a container.
- [Git](https://git-scm.com/) installed to clone and manage the repository.

## Setup and Installation
### 1. Clone the Repository
Clone the repository from GitHub to your local machine:
```bash
git clone https://github.com/Enes-hacker/user-list-app.git
cd user-list-app