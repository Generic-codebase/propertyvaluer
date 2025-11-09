# NZ Property Value Estimator

A comprehensive property valuation and renovation calculator tool designed specifically for the New Zealand real estate market.

## Features

### Property Value Estimation
- Estimate property values across 12 major NZ regions
- Support for multiple property types (House, Townhouse, Apartment, Lifestyle Block)
- Advanced valuation algorithm accounting for:
  - Regional price variations
  - Property size (floor area and land)
  - Number of bedrooms and bathrooms
  - Property age and depreciation
  - Overall condition

### Renovation Value-Add Calculator
Calculate potential value increases from 11 common NZ renovation projects:
- Kitchen Renovation
- Bathroom Renovation
- Adding Bedrooms/Bathrooms
- Deck/Outdoor Living Areas
- Heat Pump Installation
- Insulation Upgrades
- Interior & Exterior Painting
- Flooring Replacement
- Landscaping

Features include:
- Cost vs. Value analysis
- ROI calculations
- Net gain/loss projections

### User Features
- **Google Authentication**: Sign in to save and manage projects
- **Save/Load Projects**: Store multiple property estimations
- **Quote Request System**: Connect with NZ property professionals
- **Responsive Design**: Works on mobile and desktop

## Setup

### Basic Usage
1. Open `index.html` in a web browser
2. Fill in property details
3. View estimated property value
4. Optionally add renovation calculations

### Google OAuth Setup
To enable user authentication and project saving:

1. Create a Google Cloud Project at [Google Cloud Console](https://console.cloud.google.com)
2. Enable the Google Sign-In API
3. Create OAuth 2.0 credentials (Web application)
4. Add authorized JavaScript origins (your domain)
5. Copy your Client ID
6. Update line 911 in `index.html`:
   ```javascript
   const GOOGLE_CLIENT_ID = 'YOUR_CLIENT_ID_HERE';
