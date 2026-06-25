# listed_companies_10-k_downloader
A lightweight Python demo for downloading SEC 10-K annual reports (HTML/TXT) from publicly listed companies since 2000.

## Features

- Download SEC 10-K filings from EDGAR
- Supports HTML / HTM / TXT formats
- Covers filings since 2000+
- Simple ticker input workflow
- Includes SEC-compliant request headers
- Lightweight demo with sample outputs

## Demo
Output Directory Screenshot/Successful Download Example
- <img width="592" height="1122" alt="image" src="https://github.com/user-attachments/assets/00d7fbc3-33a6-42b7-b021-09c60394265a" />

#10K_filing
output file

## Technical Details

- Python
- requests
- BeautifulSoup
- SEC EDGAR filing index parsing
- HTML/TXT document extraction
- File system organization

## SEC Compliance

This demo includes:
- Custom User-Agent headers
- Request throttling
- Small-scale educational usage only

##Architecture
List of Listed Companies
↓
Ticker Cleaning
↓
ticker → CIK
↓
Get 10-K filing records after 2000
↓
Run crawling (i.e., download)

## Limitations

- Demo version only downloads a small number of filings
- No multiprocessing
- No full SEC index mirroring
- Limited error recovery
