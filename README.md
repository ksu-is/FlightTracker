✈️ Flight Tracker – Live Flight Status, SMS Alerts & Real-Time Map

A Python-based flight-tracking application that gives live flight updates, real-time aircraft position, SMS notifications, and a desktop GUI for easy monitoring.
This application pulls live flight status from FlightStats, estimates live aircraft position using FlightRadar24's public JSON feed, and provides Twilio SMS alerts for major events such as:

 - Flight delays

 - Status changes

 - Landing / arrival notifications

The GUI includes a real-time map (Matplotlib + Tkinter) that updates every 2 minutes.

🚀 Features
🔹 Live Flight Status Tracking

  - Fetches flight status, scheduled vs actual departure/arrival times

  - Scrapes public FlightStats pages for updated flight information

🔹 Real-Time Aircraft Position Map

  - Pulls global aircraft feed from FlightRadar24

  - Identifies aircraft by callsign

  - Displays aircraft latitude/longitude

  - Shows aircraft altitude and speed

  - Renders a live point on a world map inside the GUI

🔹 SMS Notifications (Twilio)

Notify the user instantly when:

 - ✈️ Status changes (e.g., "taxiing", "en-route", “scheduled”)

 - ⚠️ Flight is delayed

 - 🛬 Flight has landed or arrived

🔹 GUI Application

Built in Tkinter, includes:

 - Text fields for airline code & flight number

 - Start/Stop tracking buttons

 - Live status panel (status, times, last update)

 - Right-side map panel showing plane position

 - Automatic refresh every 2 minutes

https://github.com/shallvhack/Flight-Tracker?utm_source=chatgpt.com
