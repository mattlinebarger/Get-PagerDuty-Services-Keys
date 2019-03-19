# Get PagerDuty Services Keys

Save [PagerDuty](https://www.pagerduty.com/) Services' Service Names, Service IDs, Escalation Policy IDs, &amp; ServiceNow Webhook IDs as an [Microsoft Excel](https://products.office.com/en-us/excel) file so data can be manually added to [ServiceNow](https://www.servicenow.com/) once the PagerDuty app is installed.

## Prerequisites

* PagerDuty Account
* PagerDuty v2 API Key (read only)
* Python 2.x
* The following Python modules: os, json, requests, sys, openpyxl

## Installation

1.  Download project or just 'getkeys.py'.
2.	Ensure 'getkeys.py' has execution rights. `chmod +x getkeys.py`

## Example Usage

`./getkeys.py -k <PagerDuty v2 API Key>`
`./getkeys.py -key <PagerDuty v2 API Key>`
