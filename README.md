# Log File Analysis Tool

This is a Python script for analyzing web server log files. It provides insights into:
- Requests per IP address.
- Most frequently accessed endpoints.
- Detection of suspicious activities such as multiple failed login attempts.

## Features

- **Count Requests per IP:** Tracks the number of requests made by each IP address.
- **Most Accessed Endpoint:** Identifies the endpoint with the highest number of hits.
- **Suspicious Activity Detection:** Flags IPs with failed login attempts exceeding a configurable threshold.
- **Save Results to CSV:** Outputs analysis results into separate CSV files for further investigation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/2004-AlokSINGH/NetworkLog-Analysis-Script.git
