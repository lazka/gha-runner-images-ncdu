# GitHub Actions Windows Disk Usage Scanner

GitHub Actions workflow that scans Windows runner disk usage using ncdu.

## What it does

* Runs on Windows runners (2022, 2025, 11-arm)
* Scans C: and D: drives with ncdu
* Uploads JSON reports as artifacts

## Usage

* Manually trigger from Actions tab to generate disk usage reports.
* Download reports from the workflow run artifacts.
* Run `ncdu -f <report.json>` to view the reports locally.
