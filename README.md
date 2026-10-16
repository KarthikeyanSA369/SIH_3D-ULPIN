# 3D ULPIN & Vertical Property Mapping

A web-based application for **3D property visualization, cadastral mapping, and vertical property management**. The project provides an interactive interface for viewing property information, exploring mock datasets, and performing property validation.

## 🚀 Features

- **3D Property Viewer** – Explore property information through an interactive 3D interface.
- **Cadastral Mapping** – Visualize land parcels and property boundaries.
- **Vertical Property Mapping** – Support the visualization of vertically structured properties.
- **Property Validation** – Run validation checks on property data.
- **Mock Datasets** – Explore application features using sample data.
- **Gemini AI Integration** – Optional integration with Google Gemini API for AI-powered features.

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript
- **Build Tool:** Vite
- **Package Manager:** npm
- **AI Integration:** Google Gemini API (optional)

## 📋 Prerequisites

Make sure the following software is installed:

- [Node.js](https://nodejs.org/) (Node.js 22 recommended)
- npm (included with Node.js)
- Git

## 📥 Installation

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

### 2. Navigate to the Project Directory

```bash
cd SIH_Problem_Statement2-main
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables (Optional)

If you want to enable Gemini AI features, create a `.env` file from the example:

**Windows PowerShell:**

```powershell
Copy-Item .env.example .env
```

Add your Gemini API key to the `.env` file:

```env
GEMINI_API_KEY=your_actual_api_key
```

Get an API key from [Google AI Studio](https://aistudio.google.com/).

**Note:** The core 3D viewer, cadastral mapping, mock datasets, and validation features can run without the Gemini API key.

Never commit your actual `.env` file or expose API keys in a public repository.

### 5. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in the terminal. By default, the application is configured to run at:

http://localhost:3000

## 📦 Available Commands

| Command | Description |
|---|---|
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts the development server |
| `npm run build` | Creates a production build in the `dist/` directory |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs the configured TypeScript checks |

## 📁 Project Structure

```text
SIH_Problem_Statement2-main/
├── src/                 # Application source code
├── public/              # Static assets, if present
├── .env.example         # Environment variable template
├── .gitignore           # Git ignore rules
├── App.tsx              # Main application component, if at root
├── package.json         # Dependencies and npm scripts
├── vite.config.ts       # Vite configuration
├── metadata.json        # Application metadata
└── README.md            # Project documentation
```

*Note: The exact locations of files and folders may vary depending on the repository structure.*

## 🧪 Validation

Run the configured checks:

```bash
npm run lint
npm run build
```

If both commands complete successfully, the project has passed the corresponding checks.

## 🔐 Environment Variables

| Variable | Purpose | Required |
|---|---|---|
| `GEMINI_API_KEY` | Enables configured Gemini AI functionality | No |

Keep API keys private. For production deployment, configure secrets through the hosting platform rather than committing them to GitHub.

## 🌐 Deployment

The application can be deployed to a static hosting platform that supports Vite applications, provided all required features work in that environment.

1. Run `npm run build`.
2. Deploy the generated `dist/` directory.
3. Configure environment variables and any required API services.
4. Test the deployed application.

**Important:** If Gemini requests or other features require secret API keys, use a backend proxy rather than exposing private keys in browser-side code.

## 🎯 Project Objective

The objective of this project is to support digital land and property management through interactive 3D visualization, cadastral mapping, and vertical property representation.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch to GitHub.
5. Open a pull request.

## 📄 License

Add the appropriate license before distributing or reusing this project publicly.

---

**Developed as part of a Smart India Hackathon (SIH) project.**
