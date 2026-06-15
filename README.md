# 📋 County Tracker

Track every county you visit using GPS and the US Census Bureau API.

## Features

- **Real-time GPS Tracking** - Get your current location with GPS coordinates
- **County Detection** - Automatically identify which county you're in using the Census API
- **Visit History** - Keep track of all counties you've visited
- **Statistics** - See how many counties and states you've visited
- **Auto-Tracking** - Continuously update your location as you travel
- **Offline Storage** - All data saved locally in your browser
- **Mobile-Friendly** - Works great on phones and tablets

## How to Use

1. **Allow Location Access** - When prompted, grant permission to access your GPS location
2. **Get Location** - Click the "Get Location" button to see your current county
3. **Auto-Track** - Click "Start Auto-Tracking" to continuously track as you travel
4. **View History** - See all visited counties in the list below
5. **Clear Data** - Delete individual counties or clear all data

## Data Privacy

- All data is stored locally in your browser (localStorage)
- No data is sent to external servers except for location-to-county lookups via Census API
- GPS coordinates are only used to identify your county

## How It Works

1. Browser accesses your GPS location (with permission)
2. App sends coordinates to the US Census Bureau Geocoding API
3. Census API returns the county and state for those coordinates
4. County is added to your visited list and saved locally

## Browser Requirements

- Modern browser with Geolocation API support
- HTTPS connection (required for GPS access)
- JavaScript enabled

## Deployment

This app is deployed to GitHub Pages and automatically updates when changes are pushed to the main branch.

**Live Demo:** https://mnwt172.github.io/county-tracker/
