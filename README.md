# Employee Review System

## Problem Statement

The goal of this project is to create an application that allows employees to submit feedback toward each other's performance. The application will have separate views for administrators and employees, with specific features for each role.

## Features

### Admin View

- **Add/Remove/Update/View Employees:** The admin can perform CRUD operations on employee records, including adding, removing, updating, and viewing employee details.

- **Add/Update/View Performance Reviews:** The admin can create and manage performance reviews. They can add new reviews, update existing reviews, and view performance review details.

- **Assign Employees for Performance Review:** The admin can assign employees to participate in another employee's performance review. They can choose which employees are required to provide feedback for a specific review.

### Employee View

- **List of Performance Reviews Requiring Feedback:** Employees can view a list of performance reviews that require their feedback. This list will include the performance review details and the employee(s) being reviewed.

- **Submit Feedback:** Employees can submit feedback for performance reviews they are assigned to. They can provide their comments and ratings regarding the reviewed employee's performance.

### Authentication

- **Login:** The application provides a single login system where both admins and employees can log in using their credentials.

- **Registration:** Employees can register themselves into the system. However, only an admin can assign admin privileges to an employee.

## Getting Started

Follow the steps below to get the Employee Performance Feedback Application up and running on your local machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/employee-performance-feedback.git
   ```

2. Navigate to the project directory:

   ```bash
   cd employee-performance-feedback
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add the necessary environment variables with their respective values:

     ```plaintext
     DATABASE_URL=your-mongodb-connection-string
     JWT_SECRET=your-jwt-secret
     ```

5. Start the application:

   ```bash
   npm start
   ```

6. Access the application in your browser at `http://localhost:3000`.

## Usage

- Access the application in your preferred web browser.
- Log in using your credentials as either an admin or an employee.
- Navigate through the different views to perform the desired actions, such as adding employees, creating performance reviews, assigning employees, providing feedback, etc.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

We would like to acknowledge the following resources and libraries that have been instrumental in the development of this application:

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoose

js.com/)
- [Passport.js](http://www.passportjs.org/)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [Bootstrap](https://getbootstrap.com/)
