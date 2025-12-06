# Autus Trades - Client Booking System

Client-side appointment booking interface for Autus Trades.

## Features

- Intuitive appointment booking interface
- Multi-step booking process
- Date and time slot selection
- Form validation
- Confirmation page with booking details
- Responsive design for all devices

## Structure

```
├── index.html       # Main booking page
├── css/
│   └── styles.css   # Styles
└── js/
    └── app.js       # Booking logic
```

## Configuration

Update the API URL in `js/app.js`:

```javascript
const API_URL = 'https://your-backend.onrender.com/api/appointments';
```

## Deploy to Vercel

```bash
vercel
```

Or push to GitHub and import in Vercel dashboard.

## Tech Stack

- HTML5, CSS3, JavaScript
- Font Awesome icons
- Google Fonts (Inter)
