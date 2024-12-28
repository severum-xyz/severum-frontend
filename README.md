# Severum Frontend

## Overview

**Severum Frontend** is the minimalistic user interface for the Severum Web3 security platform. Built using React and Vite, it integrates with Severum Core to provide an interactive environment for editing, saving, and testing Solidity smart contracts using Monaco Editor.

## Features

- **Monaco Editor Integration:** A powerful in-browser code editor for writing Solidity smart contracts.
- **API Integration:** Seamlessly interacts with Severum Core for saving contracts, building projects, and running tests.
- **Minimalistic Design:** Focused on simplicity and ease of use, catering to Web3 security researchers and developers.

## Installation

To get started with Severum Frontend, follow these steps:

### 1. Clone the repository
```
git clone https://github.com/severum-xyz/severum-frontend.git
cd severum-frontend
```

### 2. Install Dependencies

Ensure you have Node.js and npm installed. If not, install them from [Node.js's official website](https://nodejs.org/).

Install the required packages:
```
npm install
```

### 3. Run the Development Server

Start the Vite development server:
```
npm run dev
```

The application will be available at `http://localhost:5173`.

## Project Structure

- `src/components/`: Contains reusable UI components like `MonacoEditor.tsx`.
- `src/utils/`: Includes utility files such as `api.ts` for API integration.
- `App.tsx`: Main React component that brings everything together.
- `main.tsx`: Entry point for rendering the React app.
- `package.json`: Contains project dependencies and scripts.
- `index.html`: Main HTML file used by Vite to load the React app.

## Contributing

Contributions are welcome! To contribute:
- Fork the repository and create a feature branch.
- Follow the minimalistic design approach for any UI enhancements.
- Submit a pull request after testing your changes.

### License

Severum Frontend is open for contributions under the [MIT License](LICENSE).

## Contact

For questions or feedback, please reach out to the Severum team at **contact@severum.xyz**.

---
**Note:** This is an MVP version focused on delivering core functionality with minimal features. Future versions will include additional capabilities and enhanced design.
