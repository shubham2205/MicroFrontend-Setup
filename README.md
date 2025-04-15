# MicroFrontend-Setup
A microfrontend architecture showcasing a Next.js 15 host application integrated with a React 18 remote app. This repository demonstrates module federation for seamless component sharing, optimized performance, and scalable frontend development.


Repository Structure
host-app: Next.js 15 application serving as the host app
remote-app: React 18 application serving as the remote app

Host App (Next.js 15)
cd host-app
npm install
npm run dev

Remote App (React 18)
cd remote-app
npm install
npm start


How it Works
The host app (Next.js 15) serves as the main entry point for the application.
The remote app (React 18) is built and served as a separate module.
The host app uses the next/dynamic module to dynamically import the remote app.
The remote app is rendered as a separate component within the host app.


Benefits
Scalability: Each app can be developed, tested, and deployed independently.
Maintainability: Changes to one app do not affect the other app.
Flexibility: New apps can be added or removed as needed.
