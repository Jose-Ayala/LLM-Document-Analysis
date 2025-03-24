# SEC 8-K Filing Analysis

This project processes SEC 8-K filings to extract key details related to new or updated products announced by companies. The analysis utilizes data fetched from the SEC's EDGAR database and uses the Ollama model for Named Entity Recognition (NER) to identify and extract relevant product information.

## Project Overview

The main goal of this project is to:

- Fetch company data from the SEC API.
- Retrieve 8-K filings for each company.
- Use natural language processing (NLP) techniques to identify mentions of new or updated products in 8-K filings.
- Process the extracted data and store it in a structured format (CSV).
- Filter and clean the extracted data for meaningful insights.

## Key Features

- **Data Fetching:** Uses the SEC API to obtain company tickers and retrieve filings from the EDGAR database.
- **NLP Processing:** Utilizes Ollama's LLM model to analyze the content of 8-K filings and extract product-related information.
- **Data Cleaning & Filtering:** Filters out unnecessary rows and ensures only relevant information is kept for further analysis.
- **Output:** The processed data is saved in a CSV file format for further use.

## Technologies Used

- **Python**: Core programming language used for the analysis.
- **pandas**: For data manipulation and storage in DataFrame.
- **BeautifulSoup**: For parsing and navigating HTML/XML content from 8-K filings.
- **Ollama**: Used to run language model-based extraction on the filing content.
- **csv**: For writing and reading structured data.
- **requests**: To fetch data from web APIs.

## Project Structure

```plaintext
SEC 8-K Filing Analysis/
├── SEC 8-K Analysis.ipynb       # Jupyter Notebook with the complete analysis
├── SEC 8-K Analysis.csv         # Initial raw data (if applicable)
├── SEC 8-K Analysis Filtered.csv # Final filtered data after processing
├── README.md                    # Project overview and instructions
