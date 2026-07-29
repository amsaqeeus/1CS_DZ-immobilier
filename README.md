🏢 1CS DZ-Immobilier

1CS DZ-Immobilier is a full-stack real estate management and listing platform tailored for property listings, rentals, and sales. Built with a Node.js Express backend API and a modern web interface, it offers key functionalities for handling property data, uploading property images, managing user listings, and handling client inquiries.
🛠️ Tech Stack & Features
Backend Stack

    Runtime Environment: Node.js

    Web Framework: Express.js

    Database / Models: Node/MongoDB or SQL integration

    Authentication & Security: bcrypt for secure password hashing & JWT / session management

    File & Image Uploads: busboy / multer handling multipart form data (supports image uploads like PNG/JPEG)

    Environment Configuration: Support for _config.yml and .env variables

Key Features

    🏠 Property Management: Create, view, update, and remove property listings (apartments, villas, land, etc.).

    🖼️ Image Management: Upload and serve high-resolution property pictures.

    🔒 User Authentication: Secure password hashing using native bcrypt binaries.

    📦 RESTful API: Structured API endpoints handling data streaming (busboy/readable-stream) and JSON body parsing.

📂 Directory Structure
Plaintext

1CS_DZ-immobilier-main/
├── Backend/
│   ├── images/              # Stored uploaded property photos and assets
│   ├── node_modules/        # Installed Node.js dependencies
│   ├── _config.yml          # Backend configuration settings
│   ├── package.json         # Dependencies and script definitions
│   └── package-lock.json    # Locked dependency tree
├── .codegpt                 # CodeGPT configuration / workspace settings
└── .gitignore               # Ignored files (node_modules, logs, etc.)

🚀 Getting Started

Follow these steps to set up and run the backend locally:
Prerequisites

    Node.js (v14.x or higher recommended)

    npm (Node Package Manager)

Installation

    Clone the repository:
    Bash

    git clone https://github.com/your-username/1CS_DZ-immobilier.git
    cd 1CS_DZ-immobilier-main/Backend

    Install backend dependencies:
    Bash

    npm install

    Configure Environment:
    Update or set up your _config.yml or environment variables for your database connection strings, server port, and secrets.

💻 Running the Application
Development Mode

Start the backend server with auto-reloading enabled (via nodemon):
Bash

npm run dev

(Or run npx nodemon directly inside the Backend directory)
Production Mode

Start the standard Node.js application server:
Bash

npm start

📸 Image & File Uploads

    Property images uploaded through forms are saved directly to the Backend/images/ folder.

    Handled seamlessly using multipart form-data parser utilities (busboy/append-field).

🛡️ License & Contributing

    Fork the repository

    Create your feature branch (git checkout -b feature/AmazingFeature)

    Commit your changes (git commit -m 'Add some AmazingFeature')

    Push to the branch (git push origin feature/AmazingFeature)

    Open a Pull Request
