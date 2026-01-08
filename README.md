### Data ingestion details

The VPN log file was manually uploaded using Splunk’s **Add Data**
workflow to simulate a controlled onboarding scenario.

Configuration used during ingestion:
- Source type: JSON
- Sourcetype: `_json`
- Index name: `VPN_Logs`

This step was intentionally included to reflect real-world SIEM usage,
where analysts are often required to validate log ingestion before
analysis begins.

