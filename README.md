# IP Address Tracker

## Overview
The **IP Address Tracker** is a web application designed to provide geographical and network-related details about an IP address. This tool is essential for users who need to track IP addresses for analytics, security, or personal curiosity.

## Features
- Retrieve geographical location (city, region, country).
- Display network information, including ISP and timezone.
- Interactive map to visually locate the IP address.
- User-friendly interface with a search functionality.
- Support for both IPv4 and IPv6 addresses.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js (optional, if server-side functionality is required)
- **API Integration**:
  - IP Geolocation API (e.g., [ipify](https://geo.ipify.org) or [ipstack](https://ipstack.com)) for retrieving IP data.
  - Mapping API (e.g., [Leaflet.js](https://leafletjs.com) or Google Maps) for visual representation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/ip-address-tracker.git
   cd ip-address-tracker
   ```

2. Install dependencies (if backend is implemented):
   ```bash
   npm install
   ```

3. Add your API keys:
   - Replace placeholder keys in the `config.js` file with your own API keys for the IP Geolocation and Mapping APIs.

4. Start the application:
   - For a static implementation: Open `index.html` in your browser.
   - For a dynamic implementation: Run the server and access the application via `http://localhost:3000`:
     ```bash
     npm start
     ```

## Usage
1. Enter the desired IP address or domain in the search bar.
2. Click the "Track" button.
3. View the details such as location, ISP, and timezone on the page.
4. Use the interactive map to visually explore the location.

## Screenshots

### Homepage
![Homepage](screenshots/homepage.png)

### Search Results
![Search Results](screenshots/search-results.png)

## Contributions
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your forked repository.
4. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

