# Eset Remote Administrator TA for Splunk

## Overview
This TA for Splunk provide fields extractions from Eset Remote Administrator logs and mapping to the Malware CIM


## Details
TA-eset-ra
Eset Remote Administrator TA for Splunk. Fields extractions and CIM mapping

## Configurations
Install this TA from splunkbase or manually on your search heads
Configure port listening in Data Inputs
Enjoy your data!

## Recommendations
We recommend to separate your data and create index specially for this TA.

## Updates history
### [1.0.0]

- Initial release
- Data model mapping Malware -> Blocked
- Some problems with timestamp
- Actions "cleaned by deleting", "connection terminated" and "deleted" = action "blocked" for good CIM mapping
