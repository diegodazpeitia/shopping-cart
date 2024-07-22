# React Hook Form - Simple Login Form Example

This project is a simple demonstration of using `react-hook-form` in a React application. The purpose is to implement a basic login form where users can input their email and password to log in. This serves as a practical introduction to `react-hook-form`, a powerful library for managing forms in React with ease.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/react-hook-form-login.git
   cd react-hook-form-login
   ```

2. **Install Dependencies**

   Make sure you have Node.js and npm installed on your machine. Then, install the project dependencies.

   ```bash
   npm install
   ```

3. **Run the Application**

   Start the development server to run the application locally.

   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## About the Project

### Project Structure

The core logic of the login form is implemented in `src/Login.jsx`. Here's a breakdown of the main components:

- **Login Component (`src/Login.jsx`)**: This component uses `react-hook-form` to manage form state and validation.
  - It handles form submission with `handleSubmit` from `react-hook-form`.
  - Validates the email field for required input using `register` and shows an error message if the field is empty.
  - Handles form submission using `onSubmit` function, where it checks against stored user data in localStorage.

### Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **react-hook-form**: A library for managing form state and validation in React applications.
- **CSS**: Basic styling is applied using CSS classes defined in `App.css`.

## Learn More

To learn more about `react-hook-form`, visit the [official documentation](https://react-hook-form.com/).

## Author

- **Diego Azpeitia**
- GitHub: [github.com/diegodazpeitia](https://github.com/diegodazpeitia)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the README further with additional sections, screenshots, or any other details that might be relevant to your project. This structure provides a clear overview of your project using `react-hook-form` for a login form, aimed at helping others understand and get started with your codebase.
