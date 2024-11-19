A basic concept for a stock trading app in JavaFX, utilizing a simple MySQL database. Created with https://github.com/amitbarel.

Initialization:

The SQL Database folder contains the MySQL files needed to create the database. CreateDB will create the project, while StocksCreateTable will initialize all tables within the database. Fill in the PASS variable in DBController.java in order to connect to the database.


To have basic stocks to test selling and buying, import CompanyTable and InventoryTable as .csvs into MySQL through the MySQL UI.

Design Patterns used for this project:
Observer (StockMarket, Trader)
Command (Broker)
