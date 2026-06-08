# TravelPlaningProject_2021_Script

A web-based travel planning application with user authentication and trip management features.

## Features

- User login and signup with secure PHP API
- Trip planning and itinerary management
- Android app support
- CDN-hosted assets

## Project Structure

```
├── API/          # PHP login/signup API (SQL injection & XSS protected)
├── Example/      # Example usage files
├── android/      # Android app integration
├── Index.php     # Main entry point
├── login.php     # Login page
├── style.css     # Stylesheet
└── cdn.php       # CDN asset loader
```

## Getting Started

1. Clone the repository
2. Configure your database in `API/DataBaseConfig.php`
3. Deploy to a PHP-capable web server
4. Open `Index.php` in your browser

## Authentication API

See [API/README.md](API/README.md) for full documentation on the login/signup API.

## Requirements

- PHP 7.0+
- MySQL database
- Web server (Apache/Nginx)
