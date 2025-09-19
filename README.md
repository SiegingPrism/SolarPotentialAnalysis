# SolarPotentialAnalysis
☀️ Advanced Solar Energy Analysis Platform
An interactive, single-page web application for comprehensive solar energy analysis. This platform allows users to assess solar potential, configure photovoltaic (PV) systems, and perform detailed financial modeling for any location in the world.

🚀 Features
Interactive Global Map: Uses Leaflet.js to provide a dynamic map for selecting analysis locations by clicking, searching, or using geolocation.

Detailed System Configuration: Allows users to specify system size (kW), panel technology (Monocrystalline, Polycrystalline, etc.), installation type, and orientation (tilt/azimuth).

Financial Modeling: Calculates key financial metrics including annual savings, payback period, and Levelized Cost of Energy (LCOE). Supports multiple currencies (₹, $, €).

Comprehensive Analysis: Generates essential performance data such as annual energy generation (kWh), capacity factor, and CO₂ emissions avoided.

Dynamic Results Visualization: Presents monthly energy generation data in an easy-to-understand bar chart using Chart.js.

Report Generation & Export: Users can generate a printable HTML report or export the full analysis data as a JSON file.

User-Friendly Interface: Features a clean, tab-based layout, a real-time system log, and intuitive user notifications.

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+ Object-Oriented approach with Classes)

Mapping: Leaflet.js - An open-source JavaScript library for interactive maps.

Charting: Chart.js - A simple yet flexible JavaScript charting library.

Geospatial Analysis: Turf.js - For advanced geospatial analysis and calculations (used for area calculations from map drawings).

⚙️ Getting Started
This is a self-contained single-page application with no external dependencies or build steps required.

Installation
Clone the repository to your local machine:

Bash

git clone https://github.com/your-username/solar-analysis-platform.git
Navigate to the project directory:

Bash

cd solar-analysis-platform
Running the Application
Simply open the index.html file in any modern web browser (like Google Chrome, Firefox, or Microsoft Edge).

Bash

# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
📖 How to Use
Select a Location:

Click anywhere on the interactive map.

Manually enter coordinates in the Location tab.

Use the "Use My Location" button for automatic detection.

For India, use the quick-select dropdown to choose a major city.

Configure Your System:

Navigate to the Analysis tab.

Enter the desired System Size (kW).

Choose the Panel Technology and Installation Type.

Set the Tilt and Azimuth angles or use the "Auto Optimize" button.

Enter the local System Cost and Electricity Rate.

Run Analysis:

Click the "Run Complete Analysis" button.

A loading spinner will appear while the calculations are performed.

View Results:

The application will automatically switch to the Results tab.

Review the calculated metrics and the monthly generation chart.

You can now Export the data or Generate a Report.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request
