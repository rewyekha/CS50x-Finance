# C$50 Finance

C$50 Finance is a web application that allows users to manage stock portfolios by buying, selling, and viewing real-time stock prices. This project is built using **Flask** (Python web framework) and **SQLite** for database management. It also integrates with the IEX Cloud API for stock price data.

## Features

- **Register**: Users can create an account by providing a username and password.
- **Login/Logout**: Users can securely log in to their accounts and log out.
- **Quote**: Users can look up the current price of a stock by entering its symbol.
- **Buy Stocks**: Users can purchase stocks by providing the stock symbol and the number of shares they want to buy.
- **Sell Stocks**: Users can sell the stocks they own by specifying the stock symbol and the number of shares they wish to sell.
- **Portfolio**: Displays the user's stock holdings, including the number of shares owned, the current price of each stock, and the total value of each stock.
- **Transaction History**: Displays all buy and sell transactions made by the user.

## Technologies Used

- **Flask** - Python web framework
- **SQLite** - Database for storing user data, stock transactions, etc.
- **HTML/CSS** - Frontend using Bootstrap for responsive design
- **IEX Cloud API** - For fetching stock prices
- **Jinja2** - Templating engine for rendering HTML pages

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/rewyekha/CS50x-Finance.git
   cd cs50-finance
   ```

2. **Install dependencies**:

   Make sure you have **Python** and **pip** installed. Then, install the necessary packages using the following command:

   ```bash
   pip install -r requirements.txt
   ```

3. **Setup the database**:

   The project uses an SQLite database. You can set up the database by running:

   ```bash
   sqlite3 finance.db < schema.sql
   ```

4. **Run the Flask app**:

   Start the Flask server locally:

   ```bash
   flask run
   ```

   By default, the app will run at `http://127.0.0.1:5000/`.

## Deployment

This project is deployed on [Koyeb](https://koyeb.com/), a cloud platform for hosting apps. To view the live application, visit the following URL:

**[Live Demo](https://tory-filippa-reyas-33204cd3.koyeb.app/)**

## Usage

1. **Create an Account**: Register with a unique username and password.
2. **Login**: Use your credentials to log in.
3. **View Portfolio**: Check your portfolio, which includes your stock holdings and available cash.
4. **Buy Stocks**: Look up a stock symbol, choose the number of shares, and buy them.
5. **Sell Stocks**: Select the stock you want to sell, enter the number of shares, and complete the transaction.
6. **Transaction History**: View all past transactions, including buys and sells.

## Future Features

- **Change Password**: Allow users to change their password.
- **Add Cash**: Allow users to add more money to their account.
- **Real-time Updates**: Implement real-time updates for stock prices.

## Testing

- **Register an Account**: Test user registration and login functionality.
- **Stock Quote**: Test the stock quote feature by searching for stock symbols.
- **Buying and Selling**: Verify that buying and selling stocks updates the portfolio and transaction history correctly.
- **Error Handling**: Test invalid inputs such as invalid stock symbols, non-integer shares, and insufficient funds.

## Contributing

Feel free to fork the repository and submit pull requests. Any contributions, bug fixes, or improvements are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
