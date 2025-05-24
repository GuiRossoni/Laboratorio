# Genetic Tests Application

This is a Laravel application designed for registering and managing genetic tests. The application provides a user-friendly interface for entering test details and includes validation to ensure data integrity.

## Features

- Register genetic tests with specific details including:
  - Patient Name
  - Exam Number
  - Exam Type
  - Collection Date
  - Optional Report
- Custom validation rules with error messages for user input.
- View a list of registered genetic tests.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd genetic-tests-app
   ```

3. Install dependencies:
   ```
   composer install
   npm install
   ```

4. Set up your environment file:
   ```
   cp .env.example .env
   ```

5. Generate the application key:
   ```
   php artisan key:generate
   ```

6. Run migrations to create the necessary database tables:
   ```
   php artisan migrate
   ```

7. Start the local development server:
   ```
   php artisan serve
   ```

## Usage

- Access the application in your web browser at `http://localhost:8000`.
- Navigate to the form for registering genetic tests and fill in the required fields.
- Submit the form to save the test details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.