React + Vite + shadcn/ui Starter Template
A modern React starter template built with Vite, TypeScript, Tailwind CSS, and shadcn/ui components.

🚀 Features
⚡️ Vite - Fast build tool and development server
⚛️ React 18 - Latest React with hooks support
🎯 TypeScript - Type safety and better developer experience
🎨 Tailwind CSS - Utility-first CSS framework
🧩 shadcn/ui - Beautifully designed components built with Radix UI
📦 Path Mapping - Clean imports with @/ prefix
📦 Included shadcn/ui Components
Button
Card
Input
Label
Badge
Dialog
And more...
🛠️ Getting Started
Install dependencies

npm install
Start development server

npm run dev
Build for production

npm run build
Preview production build

npm run preview
📁 Project Structure
src/
├── components/
│   └── ui/              # shadcn/ui components
├── lib/
│   └── utils.ts         # Utility functions
├── App.tsx              # Main application component
├── index.css            # Global styles with Tailwind
└── main.tsx             # Application entry point
🎨 Customization
Adding New shadcn/ui Components
This template is pre-configured with shadcn/ui. You can add more components by creating them in the src/components/ui/ directory.

Tailwind Configuration
The Tailwind configuration is set up with shadcn/ui color variables. You can customize colors and other design tokens in:

tailwind.config.js - Tailwind configuration
src/index.css - CSS custom properties for themes
TypeScript Configuration
Path mapping is configured for clean imports:

import { Button } from "@/components/ui/button";
import { cn } from "@/lib/utils";
🌗 Dark Mode
The template includes dark mode support through Tailwind's dark: classes and CSS custom properties.

📚 Learn More
Vite Documentation
React Documentation
Tailwind CSS
shadcn/ui
Radix UI
🤝 Contributing
Feel free to submit issues and enhancement requests!

⚡ Powered by Dala - The AI-powered web development platform that helps you build full-stack applications faster.

🤖 What is Dala?
Gebeya Dala is an intelligent web development platform that accelerates your React development workflow. Build, preview, and deploy web applications, and instant development environments.

🔗 Try Dala: dala.gebeya.com

Why Use Dala?
AI-Powered Development - Get intelligent code suggestions and automated component generation
Instant Preview - See your changes live in real-time sandbox environments
Zero Setup - No local environment configuration needed
Collaborative - Build and share projects with your team
Deployment Ready - One-click deployment to production
Built with ❤️ by the Dala team to help developers build faster and smarter.
