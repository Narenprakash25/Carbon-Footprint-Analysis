This project is a large language model (LLM)-powered application that analyzes the carbon footprint of your grocery runs. It uses the Aleph Alpha LLM API for semantic embeddings and Microsoft's Azure Form Recognizer for receipt data extraction via OCR. The app processes grocery receipts, calculates the carbon footprint of purchased items, and displays the analysis on a web interface built with Flask, Jinja, and Bootstrap.

Key Components:

* Flask: Backend framework to process calculations and serve the app.
* Aleph Alpha: Provides LLM-based semantic embeddings for matching items on receipts.
* Microsoft Form Recognizer: Extracts structured data from receipt images using OCR.
* Jinja & Bootstrap: Frontend template and CSS styling for the web interface.

The Process Flow of This Application:

1) User Uploads Grocery Receipt
2) Azure Form Recognizer OCR extracts structured data
3) Data cleaned and organized in a DataFrame
4) Semantic matching for unmatched items using Aleph Alpha LLM API
5) Calculate carbon footprint for each item based on quantity, weight, etc.
6) Display carbon footprint results in a user-friendly table
7) User views the analysis and recommendations for reducing footprint

