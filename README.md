This project is a large language model (LLM)-powered application that analyzes the carbon footprint of your grocery Bill of Materials.

![Alt Text](https://github.com/Narenprakash25/Carbon-Footprint-Analysis/blob/cbcf88a5e577918423ea77d3cf4ae6ee9dac1401/BoM_Example.png)

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

