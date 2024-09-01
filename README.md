Requirements:
Flask, requests, beautifulsoup4

Adds a new Flask endpoint /scrape-linkedin that allows users to search for job listings on LinkedIn by specifying job roles and locations.

Key Changes
Endpoint: /scrape-linkedin (GET)
Parameters:
job_role: Job title (default: Frontend Developer)
location: Location (default: India)
Functionality: Scrapes LinkedIn for job postings and returns details in JSON format.
