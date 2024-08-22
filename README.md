=
# Social Media App

This is a social media application built with **React.js**, **Appwrite**, and **TanStack Query**. The app allows users to create profiles, post updates, interact with other users, and more.

![image](https://github.com/user-attachments/assets/87f6a925-b183-4fd5-b40f-4a298ae594dd)


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- User authentication and authorization
- Profile creation and editing
- Post creation, editing, and deletion
- Like, comment, and share functionalities
- Real-time updates using TanStack Query
- Backend powered by Appwrite for managing users and storing data

## Technologies Used
- **React.js**: Frontend library for building user interfaces
- **Appwrite**: Backend-as-a-Service (BaaS) for user authentication, databases, and storage
- **TanStack Query**: React hooks for data fetching, caching, and synchronization

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AFTABSHIAKH786/Social-Media-Aoo.git
   cd social-media-app
2. Install dependencies:
npm install

3. Install and configure Appwrite on your server or use Appwrite Cloud.
4. Create a new project in Appwrite.
5. Create necessary collections for users, posts, comments, etc.
6. Set up authentication methods (email/password, OAuth, etc.).
7. Configure environment variables:
Create a .env file in the root directory and add the following:
VITE_APPWRITE_URL=\
VITE_APPWRITE_PROJECT_ID=\
VITE_APPWRITE_DATABASE_ID=\
VITE_APPWRITE_STORAGE_ID=\
VITE_APPWRITE_USER_COLLECTION_ID=\
VITE_APPWRITE_POST_COLLECTION_ID=\
VITE_APPWRITE_SAVES_COLLECTION_ID=\

After Completing all the setps run the commat to run it locally
npm run dev
