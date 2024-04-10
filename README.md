# Ship monitoring and alert system

## Overview:

The system uses shipping lanes and fairways data to create buffer zones around bridges and shipping lanes. It tracks ships using the AIS API and triggers SMS alerts when ships enter the buffer zone for a specified duration.

## Features:

- Data Integration:
  - Integrate shipping lanes and fairways data from US Waters Shipping Data.
  - Utilize the AIS API to track ships in real-time.
- Buffer Zone Creation:
  - Allow users to select bridges and shipping lanes from a map interface.
  - Enable users to define the buffer zone distance around the selected areas.
- Ship Tracking:
  - Continuously monitor the position of ships using the AIS API.
  - Display ship positions and trajectories on the map interface.
- Alert System:
  - Let users set a duration threshold for ships remaining in the buffer zone.
  - Trigger an SMS alert to designated contacts (road crews, bridge staff, port staff) if a ship stays in the buffer zone longer than the specified duration.

## Technical Specifications:

- Frontend:
  - Web-based interface for map visualization and user interactions.
  - Technologies: HTML, CSS, JavaScript, Leaflet.js or similar for map integration.
- Backend:
  - Server for processing data and handling API requests.
  - Technologies: Node.js, Express.js, or Python with Flask/Django.
- Database:
  - Store user settings, buffer zones, and alert configurations.
  - Technologies: PostgreSQL, MongoDB, or similar.
- SMS Integration:
  - Integrate with an SMS gateway for sending alerts.
  - Technologies: Twilio, Nexmo, or similar SMS API.
- GIS Integration:
  - Utilize GIS tools for spatial data processing and buffer zone calculations.
  - Technologies: QGIS, ArcGIS, or similar.
- Deployment:
  - Cloud hosting for scalability and reliability.
  - Technologies: AWS, Azure, or similar.
- Security and Compliance:
  - Ensure data privacy and security in accordance with relevant regulations.
  - Implement user authentication and authorization for system access."
- Testing:
  - Conduct thorough testing, including unit tests, integration tests, and user acceptance testing.
- Future Enhancements:
  - Add more data sources for comprehensive monitoring.
Integrate with other alert systems (e.g., email, mobile app notifications).
