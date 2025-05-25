# GPSafety
GPSafety is a Geographic Information System (GIS) project built in C++ that highlights crime hotspots in Toronto using OpenStreetMap and real-time data from the Toronto Police Service API. Unlike conventional navigation tools that optimize for speed, GPSafety prioritizes safety by guiding users away from high-risk areas.

![GPSafety](https://github.com/user-attachments/assets/c467b640-9c80-4920-adc8-99503e42121e)

## Features
The project was developed in four milestone phases, each building on the previous:
- **Milestone 1: Data Structures**
  - Built efficient map-loading functions from OpenStreetMap data.
- **Milestone 2: Graphics**
  - Designed an interactive UI using GTK and UofT's EZGL renderer, with a focus on simplicity, clarity and quick access to safety features.
  - | Dark Mode View | Health & Safety Points of Interests |
|--------|---------|
| ![gpsDarkMode](https://github.com/user-attachments/assets/543b183b-15d0-42e9-bf01-913d6232987e) | ![gpsHealth](https://github.com/user-attachments/assets/d2e06894-c03e-46e5-a5c5-010a70a15e8e) |
- **Milestone 3: Path Finding**
  - Used A* algorithm to compute shortest paths between intersections.
- **Milestone 4: Courier Optimization**
  - Solved multi-stop delivery with simulated annealing + 2-opt optimization.
  - ![gpsDirection](https://github.com/user-attachments/assets/25104513-9361-4b5b-be48-60790122c789)

## Safety Alerts
![gpsSafe](https://github.com/user-attachments/assets/93e94ebb-c9cf-4ad9-92b5-0e99ce584a68)
Real-time crime alerts pulled hourly from the TPS Calls API are shown directly on the map as hotspot overlays. R. Durant, “Tpscalls.live,” tpscalls.live, https://www.tpscalls.live/ (accessed Mar. 10, 2025).

## Future Development
- **Live Route Sharing**
  - Allow users to share their active path with friends/family in real-time.
- **Global Crime Integration**
  - Expand safety feature beyond Toronto to other cities.
