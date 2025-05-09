# Data Dictionary 📑

A living reference for every dataset used in the **Metro Insights** project.  
*Update this file each time you add new raw or processed data.*

## 1. Datasets Overview
| ID | File / Table | Description | Source | Frequency | Notes |
|----|--------------|-------------|--------|-----------|-------|
| DD‑01 | `gtfs_static.zip` | Metro static schedule (routes, trips, stops) | Metro Open Data | Weekly | — |
| DD‑02 | `gtfs_rt_tripupdates.json` | Real‑time trip updates (delays, predictions) | Metro Realtime API | ~30 s | — |

*(Add rows as you acquire more data.)*

## 2. Field Definitions
### Example: `trips.txt`
| Field | Type | Description | Example |
|-------|------|-------------|---------|
| `route_id` | string | Unique identifier for a route | `RD‑1` |
| `service_id` | string | Service schedule (weekday, weekend) | `WEEKDAY` |
| `trip_id` | string | Unique identifier for a trip | `T12345` |
| `trip_headsign` | string | Destination displayed to riders | `Shady Grove` |
| … | … | … | … |

*(Create a subsection for each GTFS file or database table.)*

## 3. Data Quality Notes  
- Outline known data issues, missing values, or assumptions.  
- Link to validation rules (Great Expectations) once implemented.

## 4. Revision History  
| Date | Author | Change | Commit SHA |
|------|--------|--------|-----------|
| 2025‑05‑09 | Omid Hashemi | Created skeleton | _tbd_ |
