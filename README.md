# Capture_PharmacyUpdate
This Python script updates the NABP number of a pharmacy on the CaptureRx platform using their API service.

Prerequisites
Python 3.x
requests library (install via pip install requests)
Usage
Replace the auth_token variable with your actual authentication token obtained from CaptureRx.
Set the Pharmacy list with the UUID of the pharmacy you want to update and the new NABP number in the update_values list.
Run the script.
Description
The script sends a GET request to retrieve pharmacy data from the CaptureRx API.
It then locates the pharmacy with the specified UUID and updates its NABP number.
Finally, it sends a PUT request to update the pharmacy information on the CaptureRx platform.
Important Note
Ensure that the provided UUID corresponds to an existing pharmacy in the CaptureRx system and that the NABP number is valid.

Disclaimer
This script is provided as-is and without warranty. Use it responsibly and at your own risk.
