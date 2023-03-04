#!/bin/bash

# API Scanner: A tool for scanning APIs for vulnerabilities based on the OWASP Top 10 API 2023.

# Check if OWASP ZAP is installed
if ! command -v zap.sh &> /dev/null
then
    echo "OWASP ZAP is not installed. Please install it before running this script."
    exit
fi

# Set the target API URL
API_URL="https://example.com/api"

# Set the output file path
OUTPUT_FILE="api_scan_results.html"

# Launch OWASP ZAP API scan
zap.sh -cmd -quickurl "${API_URL}" -quickprogress -apikey <API_KEY> -format html -outfile "${OUTPUT_FILE}"

# Check if scan completed successfully
if [ $? -ne 0 ]; then
    echo "OWASP ZAP API scan failed."
    exit
fi

# Display scan results
echo "API scan completed successfully. Results can be found in ${OUTPUT_FILE}."
