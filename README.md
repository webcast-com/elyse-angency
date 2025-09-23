# Elyse Escort Agency Website

## Features
A premium escort agency website built with React, TypeScript, and Tailwind CSS.
- **Responsive Design**: Works perfectly on all devices
- **Dynamic Companion Profiles**: Load companions from JSON data
- **Advanced Search & Filtering**: Filter by location, rate, and services
- **Professional Booking System**: Complete booking flow with validation
- **WhatsApp Integration**: Direct communication with companions
- **Age Verification**: Required for booking functionality
- **Featured Companions**: Highlight premium profiles
## Managing Companions
To update companion profiles, edit the `public/companions.json` file. Each companion object should include:
```json
{
  "id": "unique-id",
  "name": "Companion Name",
  "age": 25,
  "location": "City",
  "rate": 20000,
  "whatsapp": "+254712345678",
  "services": ["Service 1", "Service 2"],
  "img": "https://image-url.com/photo.jpg",
  "bio": "Professional bio description",
  "available": true,
  "featured": false
}
```
### Companion Fields:
- `id`: Unique identifier for the companion
- `name`: Display name
- `age`: Age in years
- `location`: City (Nairobi, Mombasa, Nakuru)
- `rate`: Hourly rate in KES
- `whatsapp`: WhatsApp number with country code
- `services`: Array of services offered
- `img`: URL to profile image (recommended: 400x300px)
- `bio`: Professional description
- `available`: Set to `false` to hide from listings
- `featured`: Set to `true` to highlight as featured companion
## Available Services:
- Dinner Companion
- Event Dates
- Private Meetups
- Weekend Getaways
## Development
```bash
npm run dev    # Start development server
npm run build  # Build for production
npm run preview # Preview production build
```
## Deployment
The site is configured for easy deployment to Netlify, Vercel, or any static hosting service.