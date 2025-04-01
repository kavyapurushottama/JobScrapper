# JobScraper

A Python script to scrape software developer job listings from multiple platforms and save them to a CSV file for analysis.
This tool leverages the `jobspy` library to collect job postings for "software developer" roles in India from Indeed, LinkedIn, ZipRecruiter, Glassdoor, and Google. It filters jobs posted within the last 48 hours and exports the data to `jobs.csv`.

### 🌟Features

- Multi-platform scraping: Indeed, LinkedIn, ZipRecruiter, Glassdoor, Google.
- Location-specific search (India).
- Time-filtered results (last 48 hours).
- Exports data to CSV with proper formatting.
- Easily customizable search parameters.

---

### 🔹Prerequisites

- Python 3.x
- Libraries: `jobspy`, `pandas`, `csv`

## 🚀Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/job-scraper.git
   cd job-scraper
