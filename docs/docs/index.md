# Springboard_phishing_url_detection documentation!

## Description

Create a Machine Learning Model for detection of phishing url

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://s3://url_bucket/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://s3://url_bucket/data/` to `data/`.


