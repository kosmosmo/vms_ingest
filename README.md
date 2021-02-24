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
- log in to vm 1515-deadline-1 under nto_rush
- run deadlinewebservice.exe on desktop
- run vms_ingest_monitor.bat on desktop

### Airtable
- mandatory fields: ['Record ID','File Name','Content Type','BRAND (VMS Channel)','Ingestor','VMS Record Name *Title']
- change the record Status to "Ready for Ingest"

## Documentation
### Project
- Project Path: "Y:\\TOOLS\\EmerTech\\VMS_ingest"
- XML path: "Y:\\TOOLS\\EmerTech\\VMS_ingest\\xml_files"
