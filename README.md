# gcs_unlimited_compose
Google Cloud Storage compose without limits

## The purpose of this repository is expand the functionality of the compose function for Google's Cloud Storage platform.

### GCS has a compose limit of 32 files per compose

### This limit is addressed with the included BASH script __unlimited_cloud_storage_compose.sh__

#### The process is as follows:
- Add the list of files to compose to an array
- Recursively call function to compose all files in groups of 30 until there is only a single file remaining to compose

#### Note: Intermediary files will persist in your Google Cloud Storage bucket - be mindful of storage useage.
