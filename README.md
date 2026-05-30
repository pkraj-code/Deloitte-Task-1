# Deloitte Forage - Task 1

## Overview
This project converts two different telemetry JSON formats into a unified JSON format.

## Files
- data-1.json
- data-2.json
- data-result.json
- main.py

## Implementation
The following functions were implemented:

- convertFromFormat1(jsonObject)
- convertFromFormat2(jsonObject)

Format 1:
- Splits the location string into country, city, area, factory, and section.
- Maps operationStatus to status.
- Maps temp to temperature.

Format 2:
- Extracts device information.
- Converts ISO 8601 timestamp to milliseconds since epoch.
- Maps location and data fields to the unified format.

## Running

```bash
python main.py
