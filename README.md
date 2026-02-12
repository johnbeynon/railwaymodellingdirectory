## Railway Modelling Directory

This repo contains the source data for railwaymodelling.com

### Structure

The top level folders represent the geo that the data is for, initially just UK, but can expand as needed.

Within the geo path, `events.json` is a JSON array of events.

Each item of the array represents a single event as is structured as 

```json
  {
    "name": "The event name",
    "organizer": "The event organizer",
    "startDate": "Start date of the event in YYYY-MM-DD format",
    "endDate": "End date of the event in YYYY-MM-DD format",
    "venue": "The venue the event is being held etc",
    "address": "The postal address of the event",
    "county": "The county of the event",
    "layouts": "The number of layouts attending, eg 5, or 10+",
    "traders": "The number of traders attending, eg 5, or 10+",
    "features": [unused at the moment],
    "amenities": [unused at the moemnt],
    "description": "Description of the event",
    "latLng": "The latlng coordinates of the event",
    "url": "webpage for the event"    
  },
```
