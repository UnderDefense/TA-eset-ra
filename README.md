# Eset Remote Administrator TA for Splunk

## Overview
This TA for Splunk provide fields extractions from Eset Remote Administrator logs and mapping to the Malware CIM


## Details
Eset Remote Administrator TA for Splunk. Fields extractions and CIM mapping

## Configurations
- Install this TA from splunkbase or manually on your search heads
- Configure port listening in Data Inputs
- Enjoy your data!

## Recommendations
We recommend to separate your data and create index specially for this TA.

## Updates history
### [1.0.0]

- Initial release
- Data model mapping Malware -> Blocked
- Some problems with timestamp
- Actions "cleaned by deleting", "connection terminated" and "deleted" = action "blocked" for good CIM mapping

## Supporting
Email support during weekday from 08:00 to 16:00 by UTC time
## Contact information
- dzh@underdefense.com
- team@underdefense.com
