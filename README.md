# De Emmaculate College Website

This is the repository for the **De Emmaculate College** website, now being converted to use the **MERN stack** (MongoDB, Express, React, Node.js) instead of PHP.

## Getting Started

### Prerequisites
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (for database operations)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/de-emmaculate-college.git
   cd de-emmaculate-college
   ```
2. Install dependencies for both frontend and backend:
   ```sh
   npm install
   cd client && npm install
   ```

### Running the Development Server
Start the backend server:
```sh
npm run dev
```
Start the frontend:
```sh
cd client
npm start
```
By default, the backend will run on [http://localhost:5000](http://localhost:5000) and the frontend on [http://localhost:3000](http://localhost:3000).

## Project Structure
```
de-emmaculate-college/
│-- client/        # React frontend
│   │-- public/    # Static assets
│   │-- src/       # Source code
│   │   │-- components/  # Reusable components
│   │   │-- pages/       # React pages
│   │   │-- styles/      # Global styles
│-- server/        # Express backend
│   │-- models/    # Database models
│   │-- routes/    # API routes
│   │-- controllers/  # Route controllers
│   │-- config/    # Configuration files (e.g., database connection)
│-- .gitignore     # Git ignore file
│-- package.json   # Project dependencies & scripts
│-- README.md      # Project documentation
```

## Technologies Used
- **MongoDB** - NoSQL database
- **Express.js** - Backend framework
- **React.js** - Frontend library
- **Node.js** - Server-side JavaScript runtime
- **Tailwind CSS** - Utility-first CSS framework
- **ESLint & Prettier** - Code linting & formatting

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License
This project is licensed under the **MIT License**.

## Contact
For any inquiries, reach out to [joesefair@gmail.com](mailto:joesefair@gmail.com).
