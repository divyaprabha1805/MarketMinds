# MarketMinds

MarketMinds is a JavaFX desktop application with a MySQL backend designed for managing stock portfolios, tracking transactions, and viewing market data. The application provides real-time stock updates and a user-friendly interface for effective portfolio management.

## Features

- Real-time stock updates
- Tree-view displays for company and stock details
- Customizable watchlists
- Comprehensive data visualizations
- Transaction tracking for buying and selling stocks
- Implemented using the MVC (Model-View-Controller) design pattern

## Technologies Used

- **Programming Language:** Java
- **GUI Framework:** JavaFX
- **Database:** MySQL

## Initialization

To set up the project, follow these steps:

1. **Database Setup:**
   - The SQL Database folder contains the MySQL files needed to create the database.
   - Use `CreateDB.sql` to create the project database.
   - Use `StocksCreateTables.sql` to initialize all tables within the database.
   - Fill in the `PASS` variable in `DBController.java` to connect to the database.

2. **Import Initial Data:**
   - Import `CompanyTable.csv` and `InventoryTable.csv` into MySQL to have basic stocks for testing.

## Design Patterns Used

- **Observer Pattern:** For stock market updates and trader notifications.
- **Command Pattern:** For executing buy and sell operations through the broker.

## Installation

To run the application:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/divyaprabha1805/MarketMinds.git

    Navigate to the project directory.

    Compile and run the application using your preferred Java IDE.

Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch:
    bash

git checkout -b feature/YourFeature

Make your changes and commit them:
bash

git commit -m "Add your message here"

Push to the branch:
bash

git push origin feature/YourFeature

Open a pull request.
