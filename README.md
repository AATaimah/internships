# Internships

## Project Overview

This project is designed to scrape various websites to collect internship postings related to computer science, software engineering, and hardware engineering in Canada. The collected postings will be displayed on a website with a user-friendly interface, allowing users to filter postings by company, city, and other criteria. The website will also provide direct links to the original postings.

## Features

- Scrape internship postings from multiple websites.
- Filter postings by company, city, and other criteria.
- Display postings in a user-friendly interface.
- Redirect users to the original postings.
- Continuously scrape websites to keep the postings up-to-date.
- Remove postings that are no longer accepting applications.
- Handle different drivers and bypass captchas and proxies if necessary.

## Project Structure

- `app.py`: Main application file.
- `README.md`: Project documentation.
- `templates/`: Directory containing HTML templates for the website.
  - `index.html`: Template for the main page.
  - `posting.html`: Template for displaying individual postings.
- `urls.json`: JSON file containing the list of URLs to scrape.