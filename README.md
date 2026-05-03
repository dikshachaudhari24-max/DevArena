# DevArena

> A developer-focused web platform with integrated QR code generation and scanning — built with React and Vite.

---

## About the Project

**DevArena** is a modern web application designed for developers and tech communities. It combines a fast, lightweight frontend (powered by [Vite](https://vitejs.dev/)) with powerful QR code capabilities, enabling features such as event check-ins, developer profile sharing, session access, and real-time scanning — all from the browser.

Whether you're running a hackathon, a developer meetup, or a coding challenge, DevArena provides the tooling to manage participants and assets through seamless QR-based workflows.

---

## Key Features

- **QR Code Generation** — Create scannable QR codes for profiles, links, events, or custom data using `qrcode.react`
- **QR Code Scanning** — Scan QR codes directly from the browser camera using `html5-qrcode`
- **Fast Development Build** — Powered by Vite for near-instant hot module replacement and optimized production builds
- **Component-Based UI** — React-based component architecture for a clean and maintainable codebase
- **Developer-Ready Setup** — Modular project structure using Git submodules for scalable development

---

## Tech Stack

| Layer           | Technology                                                   |
|-----------------|--------------------------------------------------------------|
| Frontend        | React                                                        |
| Build Tool      | Vite                                                         |
| QR Generator    | [qrcode.react](https://www.npmjs.com/package/qrcode.react)  |
| QR Scanner      | [html5-qrcode](https://www.npmjs.com/package/html5-qrcode)  |
| Package Manager | npm                                                          |

---

## Project Structure
DevArena/
├── DJS_LOC/ # Main application source (submodule)
│ ├── src/ # React components and pages
│ ├── public/ # Static assets
│ └── vite.config.js # Vite configuration
├── package.json # Root scripts and dependencies
└── README.md

---
## Getting Started
### Prerequisites
- [Node.js](https://nodejs.org/) v18 or higher
- npm v9 or higher
- Git (with submodule support)
### Installation
1. **Clone the repository with submodules:**
   ```bash
   git clone --recurse-submodules https://github.com/dikshachaudhari24-max/DevArena.git
   cd DevArena
Install dependencies:
npm install
Start the development server:
npm run dev
Open your browser at http://localhost:5173
Available Scripts
Script	Description
npm run dev	Start local development server with hot reload
npm run build	Build the app for production
npm run preview	Preview the production build locally
Usage
Generating a QR Code
Navigate to the QR Generator section, enter any text, URL, or data payload, and a QR code will be rendered instantly. You can download or share it directly.

Scanning a QR Code
Open the QR Scanner and grant camera permissions. Point your device camera at any QR code — the app decodes it in real time and displays the result.

Contributing
Contributions, bug reports, and feature requests are welcome!

Fork this repository
Create a feature branch: git checkout -b feature/your-feature-name
Commit your changes: git commit -m "feat: add your feature"
Push to your branch: git push origin feature/your-feature-name
Open a Pull Request
Please follow Conventional Commits for commit messages.

License
This project is open source and available under the MIT License.

Acknowledgements
Vite — Next generation frontend tooling
qrcode.react — QR code rendering for React
html5-qrcode — Cross-platform QR code scanning
<p align="center">Made with ❤️ by <a href="https://github.com/dikshachaudhari24-max">dikshachaudhari24-max</a></p> ```
To add it to the repo manually:

Go to https://github.com/dikshachaudhari24-max/DevArena
Click Add file → Create new file
Name it README.md
Paste the content above
Click Commit changes
