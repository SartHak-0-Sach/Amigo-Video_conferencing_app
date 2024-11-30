# 🎥 Amigo - Video Conferencing App

Amigo is a robust video conferencing platform that offers secure logins, meetings, screen sharing, and more. Built using Next.js and TypeScript, it replicates popular tools like Zoom. Whether you're scheduling future meetings, joining a session, or managing participants, Amigo provides a seamless user experience.

## 📋 Table of Contents
1. 🤖 [Introduction](#-introduction)
2. ⚙️ [Tech Stack](#-tech-stack)
3. 🔋 [Features](#-features)
4. 🤸 [Quick Start](#-quick-start)
5. 🕸️ [Assets & Code](#-assets-code)
6. 🚀 [More](#-more)

## 🤖 Introduction
**Amigo** is a video conferencing app built with the latest **Next.js** and **TypeScript**. It allows users to log in securely, create and join meetings, and use various features like screen sharing, recording, and managing meeting participants. Inspired by Zoom, Amigo offers robust features for both casual and professional meetings.

- **Authentication & Security**: Login securely with social sign-on or traditional email/password.
- **Real-Time Interactions**: Everything happens in real-time, ensuring smooth communication.
- **Meeting Management**: Organize and control your meetings effortlessly.

## ⚙️ Tech Stack
| Technology          | Purpose                                         |
|---------------------|-------------------------------------------------|
| **Next.js**         | React framework for building the application   |
| **TypeScript**      | For type safety and better code management     |
| **Clerk**           | For authentication and user management         |
| **Getstream**       | For real-time messaging and stream management  |
| **Shadcn**          | For UI components and styling                   |
| **Tailwind CSS**    | For responsive and customizable styling        |

---

## 🔋 Features

👉 **Authentication**: 
- Secure login via **Clerk** with support for both social sign-on and email/password authentication.

👉 **Create & Join Meetings**: 
- Start new meetings with customizable camera and microphone settings.
- Join meetings via a simple meeting link.

👉 **Meeting Controls**: 
- Full control over meeting features like recording, screen sharing, muting/unmuting, and participant management (pinning, blocking, and unmuting).

👉 **Personal Room**: 
- A unique link for each user’s personal room, enabling instant meetings anytime.

👉 **Schedule Future Meetings**: 
- Schedule meetings for the future and access them from the 'Upcoming Meetings' page.

👉 **View Past Meetings & Recordings**: 
- Easy access to past meetings and recordings for review or sharing.

👉 **Real-time Interaction**: 
- Real-time features for messaging, screen sharing, and video/audio adjustments.

👉 **Responsive Design**: 
- Fully responsive design ensures compatibility across different devices and screen sizes.

👉 **End Meeting Controls**: 
- Participants can leave or end the meeting for everyone.

## 🤸 Quick Start

### Prerequisites
Ensure you have the following tools installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Cloning the Repository
Clone the project repository to your local machine:
```bash
git clone https://github.com/your-username/amigo.git
cd amigo
```

### Installation
Install the required dependencies:
```bash
npm install
```

### Set Up Environment Variables
Create a `.env` file in the root of the project with the following values:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholders with your **Clerk** and **GetStream** credentials. You can obtain these from their respective websites:
- [Clerk](https://clerk.com/)
- [GetStream](https://getstream.io/)

### Running the Project
Run the app locally with the following command:
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to start using the application.

## 🕸️ Assets & Code
- All assets such as UI components, images, and design files are included in the **assets/** directory.
- The code is organized with a clear structure, focusing on modularity, reusability, and scalability.

## 🚀 More
Feel free to contribute to the project by submitting issues, feature requests, or pull requests.

***Happy coding!!*** 😁✌🏻
