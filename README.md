# Portfolio vs S&P500 Performance tool

This application allows users to compare their investment portfolio's performance against the S&P500 index. The application fetches data from Google Sheets, processes it, and displays the results in a graphical format.

## Features

- Fetches investment data from Google Sheets.
- Compares portfolio performance against the S&P500.
- Displays results in a graphical format.
- Provides different time frames for analysis (14 days, 1 month, 6 months, 1 year, From the beggining).
- User-friendly interface with easy navigation.
- Unique logic for calculating profits: Get your real-time profits and compete against the same investments in the S&P500.
  - You instantly know whether you outperform S&P500 or should stick to DCA into ETFs.
-  Perfectly secure - the application does not have to store your data anywhere, it only interacts with Google Sheets.

## Application was made using these libraries

 - pandas
 - yfinance
 - gspread
 - google-auth
 - pyqtgraph
 - PySide6

## Installation

STILL WORKING ON VERSION FOR OTHER USERS

## Usage

1. Run the application
2. Follow the on-screen instructions:
    - Enter the Google Sheets link containing your investment data.
    - Click "Save" to save the link.
    - Click "Generate graph" to view the performance comparison.

## Google Sheets Format

The Google Sheets should have the following columns:
- `ticker`: The stock ticker symbol.
- `date`: The date of the transaction (format: `dd.mm.yyyy`).
- `amount`: The number of shares.
- `type`: The type of transaction (`BUY` or `SELL`).
- `price`: The price of the transaction.

## Screens

- **Welcome Screen**: Introduction and start button.
- **Input Screen**: Input field for Google Sheets link.
- **Action Screen**: Buttons to generate the graph and navigate back.
- **Result Screen**: Graphical comparison of portfolio vs S&P500 performance.

## License

All rights reserved.

This software and associated documentation files (the "Software") are the exclusive property of the author. Unauthorized copying, distribution, modification, or use of the Software, in whole or in part, is strictly prohibited.

The author reserves all rights not expressly granted herein.

For any inquiries, please contact the author at vikivyhnalek@gmail.com.

©2024 Viktor Vyhnalek. All rights reserved.

note: I did not submit here any personal API keys and stuff like that because of my privacy.
