# VMS Ingest
Airtable implementation for VMS ingesting.

## Getting Starte
### Built With
- Python3.7
- Deadline

### Dependencies
- Deadline Web Services
- request

## Usage
### Monitoring Services
1.log in to vm 1515-deadline-1 under nto_rush
2.run deadlinewebservice.exe on desktop
3.run vms_ingest_monitor.bat on desktop

### Airtable
- mandatory fields: ['Record ID','File Name','Content Type','BRAND (VMS Channel)','Ingestor','VMS Record Name *Title']
- change the record Status to "Ready for Ingest"
