# PDF Product Table Extractor

This project extracts tables from a product PDF (such as a table of contents) and converts them into structured CSV files for further processing. It allows users to easily extract and manipulate data using Python, Google Sheets, or SQL.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This tool uses `pdfplumber` to extract tables from PDFs. The extracted data is then processed into a CSV format, which can be opened in Google Sheets, loaded into SQL databases, or used in further Python workflows.

## Features
- Extracts tabular data from PDFs
- Exports data as CSV
- Easy integration with Google Sheets and SQL databases for further manipulation
- Uses Python's powerful libraries for rapid extraction

## Installation

### Prerequisites
- Python 3.x
- `pip` (Python package manager)
- Optional: SQLite3 (for database storage)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
