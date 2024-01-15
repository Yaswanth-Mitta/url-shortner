# Advanced URL Shortener Project

## Overview

This advanced URL shortener project offers additional features beyond the standard functionality. Users can enjoy both the convenience of random short URLs and the flexibility of creating custom URLs with user-defined paths.

## Main Features

### 1. Standard URL Shortening

1.1 **Random Short URLs**
   - Generate short URLs with random alphanumeric IDs.

1.2 **Click Tracking**
   - Monitor and display the number of clicks for each short URL.

1.3 **User Dashboard**
   - Allow users to view all their created short URLs in a personalized dashboard.

1.4 **User Signup**
   - Implement a user signup feature to enable personalized URL management.

### 2. Custom URL Creation

2.1 **User-Defined Paths**
   - Introduce a new route, such as `/username/a`, for users to create custom short URLs easily.

2.2 **Access Control**
   - Implement restrictions on URL access, allowing users to make URLs private or public.
   - Only users with explicit permission can redirect to certain URLs.

## Implementation Details

### Technology Stack

- **Backend:** Node.js with Express
- **Database:** MongoDB for storing user and URL data
- **Authentication:** Use JWT for secure user authentication

<!-- <!-- ### Additional Considerations

- Implement URL expiry for increased security.
- Employ rate limiting to prevent abuse.
- Use HTTPS to ensure secure communication. -->
<!-- 
## Getting Started

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Configure the MongoDB connection.
4. Run the server with `npm start`.

## API Endpoints

- `/api/shorten` - Shorten a URL (random ID).
- `/api/custom-shorten` - Shorten a URL with a custom path.
- `/api/dashboard` - View user's short URLs.
- `/api/signup` - User registration.
- `/api/login` - User login.

## Usage

1. Shorten a URL: `POST /api/shorten`
2. Create a custom short URL: `POST /api/custom-shorten`
3. View user's URLs: `GET /api/dashboard`
4. Signup: `POST /api/signup`
5. Login: `POST /api/login`

## Example

### Shortening a URL

```json
POST /api/shorten
{
  "url": "https://example.com"
} --> -->
