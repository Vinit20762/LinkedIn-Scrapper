# LinkedIn Scrapper

A project for scraping LinkedIn data using Python. The main scraping logic is implemented in a Jupyter notebook for easy experimentation and data handling.

## Features

- Extract LinkedIn profile (update this line with your specific use case)
- Output data to files within the `/data` directory
- Designed for extensibility and easy use in Jupyter Notebook

## Repository Structure

- `linkedin_scraper.ipynb` — Main Jupyter Notebook where the scraping logic is implemented.
- `requirements.txt` — List of all required Python libraries.
- `data/` — Directory where output/scraped data is stored.
- `.gitignore` — Standard .gitignore file.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Vinit20762/LinkedIn-Scrapper.git
    cd LinkedIn-Scrapper
    ```

2. **Set up a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use: venv\Scripts\activate
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook linkedin_scraper.ipynb
    ```

## Usage

- Open the notebook and follow the code cells to configure your query and run the scrapper.
- Results will appear in the `data/` directory.

## Requirements

See `requirements.txt` for the full list. Typical dependencies might include:

- `requests`
- `beautifulsoup4`
- `selenium`
- `pandas`

(Update this section with details from your own requirements.txt as necessary.)

## Disclaimer

Scraping LinkedIn may violate their Terms of Service. This project is for educational purposes only.

---

**Repository:** https://github.com/Vinit20762/LinkedIn-Scrapper
