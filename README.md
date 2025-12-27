# Currency-converter
This project is a real-time currency converter built using Python. It allows users to convert an amount from one currency to another based on the latest exchange rates available on the current day.
The application fetches live currency exchange rates from the Fixer.io API and performs accurate conversions between more than 150+ global currencies.

⚙️ How It Works

The program fetches the latest exchange rates from Fixer.io.

All rates are stored with EUR as the base currency.

User enters:

<amount> <from_currency> <to_currency>


Example:
100 USD INR


The program calculates the converted value using:
amount × (target_currency_rate / source_currency_rate)
The converted amount is displayed instantly.

▶️ Usage Instructions

Clone the repository
git clone <repository-url>


Install required dependency
pip install requests


Run the program
python currency_converter.py

Commands:
Type SHOW → View all supported currencies
Type Q → Exit the program
Type SHOW → View all supported currencies

Type Q → Exit the program
