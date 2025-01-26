# ETF Holdings Downloader

## Introduction

Exchange-Traded Funds (ETFs) are investment funds traded on stock exchanges, much like stocks. They hold assets such as stocks, commodities, or bonds and generally operate with an arbitrage mechanism designed to keep trading close to its net asset value, though deviations can occasionally occur. ETFs provide investors with a way to diversify their portfolios without having to buy individual assets.

Holdings refer to the individual assets that an ETF owns. Knowing the holdings of an ETF can help investors understand the exposure and risk associated with the ETF.

## Project Overview

This project is designed to automate the process of downloading and processing the holdings of a list of ETFs identified by their ISINs (International Securities Identification Numbers). The script performs the following tasks:

1. **Download Holdings Data**: For each ISIN in the provided list, the script downloads the holdings data from a specified URL.
2. **Process Data**: The downloaded data is processed to:
   - Remove unnecessary rows and columns.
   - Rename columns for consistency.
   - Convert asset percentages to a more readable format.
   - Insert the file name for reference.
3. **Save Processed Data**: The processed data is saved as CSV files.

## Usefulness

This project is useful for investors, analysts, and financial professionals who need to regularly update and analyze the holdings of multiple ETFs. By automating the download and processing of holdings data, it saves time and reduces the potential for manual errors. The processed data can then be used for further analysis, reporting, or integration into other financial models and tools.
