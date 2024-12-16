# Phishing-Attack-Detection
This Python-based phishing URL detector classifies URLs as legitimate or phishing by analyzing features like URL length, HTTPS, suspicious keywords, domain structure, and SSL certificate validity. A machine learning model processes these features to make predictions, with a simple Tkinter interface for user input and results display.

**Functionality:**
1. SSL Certificate Validation:
Checks if the website has a valid SSL certificate for secure communication.

2. Heuristic Analysis:
Scans the URL for suspicious keywords commonly found in phishing sites.

3. Domain Age Verification:
Retrieves domain information from the WHOIS database to check its age and other details.

4. URLScan.io Integration:
Submits the URL to URLScan.io for a thorough security scan of the website.
## Requirements

- Python 3.x
- `tkinter` (for graphical user interface)
- `scikit-learn` (for machine learning models)
- `requests` (for SSL certificate validation)
- `urllib` (for URL parsing)


### Install Dependencies

To install the required dependencies, run the following command:

```bash
pip install scikit-learn requests
