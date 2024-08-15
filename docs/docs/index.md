# MBTI Personality Detector documentation!

## Description

A transformers based approach for personality classification using text samples.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `az storage blob upload-batch -d` to recursively sync files in `data/` up to `datasets/data/`.
* `make sync_data_down` will use `az storage blob upload-batch -d` to recursively sync files from `datasets/data/` to `data/`.


