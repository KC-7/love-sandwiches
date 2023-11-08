# Love Sandwiches Data Automation

Love Sandwiches is an automated system for managing sales, stock, and surplus data for a sandwich business. This system interfaces with Google Sheets to provide an easy and intuitive way to track product movements and forecast needs.

## Live Application

The application is live at [Love Sandwiches](https://love-sandwiches-kc.herokuapp.com/), where you can view the operational interface and interact with the real-time data management system.

## Spreadsheet

Access the Google spreadsheet [here](https://docs.google.com/spreadsheets/d/1mgkHpJY_9WltiuDWG9j7IRP6mQB-KUTacO8Z_w7QlBw/edit?usp=sharing) to see the data structure used by Love Sandwiches.

## Features

- User input validation for sales data entry.
- Automated update of sales, stock, and surplus data sheets.
- Calculation of surplus data to indicate waste or stock shortages.
- Retrieval and analysis of historical sales data to forecast stock needs.

## Installation

To run this project locally, you will need to:

1. Clone the repository:
   ```bash
   git clone https://github.com/kc-7/love-sandwiches.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Google API credentials and save the JSON file as `creds.json` in the project directory.

## Usage

To use the application, execute the `run.py` script in the terminal:

```bash
python run.py
```

Follow the on-screen prompts to enter the sales data when requested.

## Acknowledgments

- Code Institute for the project template and guidance.
- Readme updated by ChatGPT.
