# Receipt Parser

## Overview
Receipt Parser is a Streamlit application designed to process receipts, display the itemized details, and help split the total cost among a group of people. By utilizing Veryfi's OCR technology, the application can extract detailed information from receipt images and allow users to calculate each person's share of the total bill, including tax, other fees, and tip.

## Features
- **Receipt Processing**: Upload a receipt image and extract item details using Veryfi's OCR.
- **Itemized Display**: View a detailed breakdown of items, quantities, and prices.
- **Cost Splitting**: Select items for each person in the group to calculate their total payment, including shared fees and tips.

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your browser and navigate to the provided local URL (usually `http://localhost:8501`).

3. Upload an image of your receipt in JPG, PNG, JPEG, or HEIC format.

4. Click the "Process Receipt" button to extract the item details.

5. View the itemized receipt details.

6. Enter the number of people in your party.

7. For each person, select the items they are responsible for to calculate their total cost, including shared fees and tips.

## Acknowledgements
- [Veryfi](https://www.veryfi.com/) for their powerful OCR API.
- [Streamlit](https://streamlit.io/) for the easy-to-use web application framework.