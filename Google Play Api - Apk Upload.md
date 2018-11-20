In Google Developer Console inside your app project, on the Credentials section, you must create a new "Service Account" "Client ID", if you have not already. And download the p12 file.
You need the service account key file, generated in the Google APIs Console into the same directory and rename it to key.p12.

On Google Play Developer Console you have to give permissions to "YOUR_SERVICE_ACCOUNT_EMAIL@developer.gserviceaccount.com" for uploading apks.

## Installation

Download Google APIs Client Library for Python (google-api-python-client): https://code.google.com/p/google-api-python-client/ or use pip:
  ```bash
    $ pip install google-api-python-client
  ```

## Execution
  ```bash
    python basic_upload_apks_service_account.py your.package.name apk-file.apk
  ```
  
Based on https://github.com/googlesamples/android-play-publisher-api/tree/master/v2/python