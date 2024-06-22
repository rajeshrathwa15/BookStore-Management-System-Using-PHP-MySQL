# BookStore-Management-System-Using-PHP-MySQL

## Project Overview
The BookStore Management System is a web-based application designed to help manage and operate a bookstore. The system includes functionalities for adding, updating, deleting, and displaying books in the inventory. 

## Front End
- HTML
- CSS
- BOOTSTRAP

## Back End
- PHP
- MySQL

## Tools & Technologies
- Wamp Server: Used for server management and hosting the application locally.
- MySQL Queries: Used for database management and operations.
- Browser: 
  - Mozilla Firefox
  - Chrome
- Text Editor: 
  - VS Code (Visual Studio Code)

## Installation and Setup Instructions

### Prerequisites
1. Install Wamp Server on your local machine.
2. Ensure you have the following browsers for testing:
   - Mozilla Firefox
   - Chrome
3. Install Visual Studio Code or any other preferred text editor.

### Steps
1. Clone the repository:
   sh
   git clone https://github.com/yourusername/BookStore-Management-System.git
   
2. Start Wamp Server:
   - Open Wamp Server and start all services.

3. Import the Database:
   - Open phpMyAdmin via your browser (usually `http://localhost/phpmyadmin`).
   - Create a new database named `bookstore`.
   - Import the SQL file provided in the `database` folder of the cloned repository into the `bookstore` database.

4. Configure the Project:
   - Place the cloned project folder into the `www` directory of your Wamp Server installation.
   - Update the database connection details in `config.php` file if necessary.

5. Run the Application:
   - Open your browser and navigate to `http://localhost/BookStore-Management-System` to view the application.

## Usage
- Add Book: Add new books to the inventory.
- Update Book: Update details of existing books.
- Delete Book: Remove books from the inventory.
- View Books: Display a list of all books available in the inventory.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- All contributors and supporters of this project.
- Open-source libraries and frameworks used in the project.

Feel free to customize and expand upon this template as needed to fit the specifics of your project.
