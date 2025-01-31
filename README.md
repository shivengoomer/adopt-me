# Citr v8 Project
#Project Deployed Url - https://adopt-me2.netlify.app/
## Project Overview
This is the **Complete Intro to React v8 project**, based on the course by Brian Holt. The project leverages React with modern tools such as Vite, React Query, and React Router DOM to create a scalable and fast web application.

---

## Features
- **React**: Fast, modular, and efficient component-based development.
- **Vite**: Lightning-fast development environment for building modern web applications.
- **React Query**: Fetch and cache API data efficiently.
- **React Router DOM**: Manage routing for a single-page application.
- **ESLint**: Enforce code quality and standards.
- **Prettier**: Automatically format code for consistency.
- **GitHub Pages Deployment**: Deploy your project with ease using `gh-pages`.

---

## Installation and Setup

### Prerequisites
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js)

### Steps to Run Locally
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shivengoomer/adopt-them.git
   cd adopt-them
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   This will start the application at `http://localhost:5173/`.

4. **Build for Production:**
   ```bash
   npm run build
   ```
   The production-ready files will be generated in the `dist` folder.

5. **Preview the Production Build:**
   ```bash
   npm run preview
   ```

6. **Deploy to GitHub Pages:**
   ```bash
   npm run deploy
   ```

---

## Folder Structure
```plaintext
src/
├── components/    # React components
├── hooks/         # Custom React hooks
├── pages/         # Page components for routing
├── styles/        # CSS or styling files
├── utils/         # Helper utility functions
├── assets/        # Static assets like images and icons
├── App.jsx        # Root React component
└── main.jsx       # React DOM entry point
```

---

## Scripts
- **`npm run dev`**: Start the development server.
- **`npm run build`**: Build the app for production.
- **`npm run preview`**: Preview the production build locally.
- **`npm run format`**: Format code using Prettier.
- **`npm run lint`**: Lint code using ESLint.
- **`npm run deploy`**: Deploy the app to GitHub Pages.

---

## Dependencies
### Core Dependencies:
- [React](https://reactjs.org/): `18.2.0`
- [React DOM](https://reactjs.org/docs/react-dom.html): `18.2.0`
- [React Router DOM](https://reactrouter.com/): `6.4.1`
- [React Query](https://tanstack.com/query/latest): `4.10.1`

### Dev Dependencies:
- [Vite](https://vitejs.dev/): `^3.2.11`
- [ESLint](https://eslint.org/): `8.24.0`
- [Prettier](https://prettier.io/): `2.7.1`
- [gh-pages](https://www.npmjs.com/package/gh-pages): `^6.1.1`

---

## Author
- **Brian Holt** - Original course instructor
- **Shiven Goomer** - Project customization and implementation

---

## License
This project is licensed under the [ISC License](https://opensource.org/licenses/ISC).

---

## Contributing
If you'd like to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

---

## Acknowledgments
- [Complete Intro to React v8 by Brian Holt](https://frontendmasters.com/courses/complete-react-v8/)
- [Vite Documentation](https://vitejs.dev/)
- [React Query Documentation](https://tanstack.com/query/latest)
