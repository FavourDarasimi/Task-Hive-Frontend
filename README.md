# Task Hive: Collaborative Task Management

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

Task Hive is a dynamic and intuitive frontend for a full-stack task management application. Built with React and Vite, it provides a seamless, collaborative environment for teams to organize projects, manage tasks, and boost productivity. The interface is designed to be clean, responsive, and user-friendly, featuring real-time updates and notifications.

## ✨ Features

- **Dashboard Analytics**: Get a comprehensive overview of your tasks, project completion rates, and team performance at a glance.
- **Workspace Management**: Create and switch between multiple workspaces to keep different projects or teams neatly separated.
- **Project Organization**: Effortlessly create, update, and manage projects. Assign team members and track progress with percentage-based completion indicators.
- **Detailed Task Tracking**: Add tasks with titles, priorities (Low, Medium, High), and due dates. Assign specific tasks to one or more team members.
- **Team Collaboration**: Invite members to your workspace via email, manage team roles, and view all members in a centralized location.
- **Real-time Notifications & Inbox**: Stay updated with real-time notifications for invites and other important events, all accessible from a dedicated inbox.
- **Customizable Profiles**: Users can update their personal information, including their name, avatar, age, and occupation.
- **Dark & Light Mode**: Switch between themes for a comfortable viewing experience in any lighting condition.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have Node.js and npm installed on your machine.

### Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/FavourDarasimi/Task-Hive-Frontend.git
    ```
2.  **Navigate to the Project Directory**
    ```bash
    cd Task-Hive-Frontend
    ```
3.  **Install Dependencies**
    ```bash
    npm install
    ```
4.  **Start the Development Server**
    ```bash
    npm run dev
    ```
5.  **Connect to Backend**
    This frontend application requires its corresponding [backend server](URL_TO_BACKEND_REPO_HERE) to be running. Ensure the API base URL in `src/context/Context.jsx` points to your running backend instance (default is `http://127.0.0.1:8000`).

## ⚙️ Usage

Once the application is running, you can:

1.  **Create an Account**: Sign up with a new username, email, and password.
2.  **Log In**: Access your dashboard using your credentials.
3.  **Manage Workspaces**: Create a new workspace or use the default one provided. You can switch between your workspaces from the header menu.
4.  **Create Projects**: Navigate to the "Projects" page and create a new project, assigning team members as needed.
5.  **Add Tasks**: Open a project and add tasks, setting their priority, due date, and assigning them to team members.
6.  **Collaborate**: Go to the "Team" page to invite new members to your active workspace via email.

## 🛠️ Technologies Used

| Technology        | Description                                       | Link                                                                   |
| ----------------- | ------------------------------------------------- | ---------------------------------------------------------------------- |
| **React**         | A JavaScript library for building user interfaces | [reactjs.org](https://reactjs.org/)                                    |
| **Vite**          | A modern frontend build tool                      | [vitejs.dev](https://vitejs.dev/)                                      |
| **Tailwind CSS**  | A utility-first CSS framework                     | [tailwindcss.com](https://tailwindcss.com/)                            |
| **React Router**  | Declarative routing for React applications        | [reactrouter.com](https://reactrouter.com/)                            |
| **React Context** | For managing global state across the app          | [reactjs.org/docs/context.html](https://reactjs.org/docs/context.html) |
| **Axios**         | Promise-based HTTP client for making API requests | [axios-http.com](https://axios-http.com/)                              |
| **Headless UI**   | Unstyled, accessible UI components                | [headlessui.com](https://headlessui.com/)                              |

## 📜 License

This project is licensed under the ISC License. See the `package.json` for more details.
