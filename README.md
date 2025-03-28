# User List App

## Overview
This is a simple web application built with React and TypeScript that fetches and displays a list of users from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users). The app includes a responsive user interface with loading and error states, styled using CSS. The project is containerized using Docker, managed with Git and GitHub, and includes modern development practices such as linting, testing, and TypeScript for type safety.

### Features
- Fetches user data from the JSONPlaceholder API.
- Displays users in a responsive grid layout.
- Includes loading and error states for better user experience.
- Styled with CSS for a clean and modern look.
- Containerized with Docker for easy setup and deployment.
- Manages state with a custom `useFetchUsers` hook.

## Prerequisites
- [Node.js](https://nodejs.org/) (version 16 or higher) installed for local development.
- [Docker](https://www.docker.com/products/docker-desktop/) installed to run the app in a container.
- [Git](https://git-scm.com/) installed to clone and manage the repository.

### 1. Install Dependencies
npm install
# or
yarn install

### 2. Run the Development Server
Start the development server:
npm start
# or
yarn start
The app should now be running at http://localhost:3000

### 3.Git Commands
1.Creating a New Repository:
```
git init
```
2.Adding and Committing Changes:
```
git add .
git commit -m "Initial commit"
```

3. Adding a Remote Repository
 ```
git remote add origin https://github.com/Enes-hacker/user-list-app.git
```
5. Pushing Changes to GitHub
```
git push -u origin main
```
6.Updating the Repository (Pull Changes)
```
git push -u origin main
```

### 4. Docker Setup
- Build the Docker Image
  
 ```
docker build -t user-list-app .
```
-  Create and Run the Docker Container
```
docker run -d -p 3000:3000 --name user-list-container user-list-app
```
- Now, visit http://localhost:3000 to view the app running in a Docker container.
-  List Running Containers
```
docker ps
```
- Stop and Remove the Container
```
docker stop user-list-container(or name you called)
```
- Remove the Docker Image (if needed)
```
docker rmi user-list-app
```
- Using Docker Compose
- To start the application using Docker Compose:
```
docker-compose up -d
```
- To stop the application:
```
docker-compose down
```

## Setup and Installation
### 1. Clone the Repository
Clone the repository from GitHub to your local machine:
```bash
git clone https://github.com/Enes-hacker/user-list-app.git
cd user-list-app

