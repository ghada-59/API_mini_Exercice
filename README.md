# API Mini Exercise

A short project that demonstrates working with public web APIs (NASA), JSON handling, data extraction and transformation, and basic exploratory data analysis using pandas. The main artifact is `API_Exercice.ipynb`, a Jupyter/Colab notebook that fetches and inspects responses from NASA's APOD (Astronomy Picture of the Day) and NEO (Near Earth Object) APIs.

## What this repo contains
- `API_Exercice.ipynb` — Jupyter/Colab notebook demonstrating:
  - Retrieving the APOD (image + metadata) from NASA's Planetary API.
  - Fetching Near-Earth Object (NEO) feed data for a date range.
  - Parsing nested JSON responses.
  - Building a tidy pandas DataFrame with selected asteroid fields.
  - Displaying images in the notebook (IPython.display).
  - Basic inspection / info about the resulting DataFrame.

## Skills demonstrated
- HTTP requests and API usage
  - Constructing requests with query parameters using `requests`.
  - Handling API keys and query parameters.
  - Basic status-code checking and JSON decoding.
- JSON parsing and nested data extraction
  - Extracting nested fields (e.g., `estimated_diameter`, `close_approach_data`).
- Data transformation and tabularization
  - Building Python dictionaries and converting to `pandas.DataFrame`.
  - Data type inspection and basic DataFrame introspection (`df.head()`, `df.info()`).
- Data presentation in notebooks
  - Displaying images inline using `IPython.display.Image`.
  - Using pandas to present a clean table in Jupyter/Colab.
- Reproducible notebook workflow
  - Colab-friendly notebook metadata and interactivity hints (convert to interactive table).
- Basic data analysis & filtering (implied — size, velocity, hazard flag available in raw API).

## Requirements
- Python 3.8+
- Recommended packages:
  - requests
  - pandas
  - jupyterlab or notebook (if running locally)
  - (optional) Google Colab for running the notebook online

Example pip install:
