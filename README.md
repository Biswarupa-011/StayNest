# StayNest
StayNest is a full-stack web application that allows users to discover, create, and review travel listings. Built with Node.js,Express.js, and mongoDB. it features user authentication, CRUD operations, and a responsive UI.

## ✨ Features

### 🔐 Authentication & User Management
- **User Registration & Login** - Secure password authentication using Passport.js
- **Password Security** - Encrypted password storage with Passport-local-mongoose
- **Flash Notifications** - Real-time feedback with custom slide-in notifications

### 🏡 Property Listings
- **Create Listings** - Upload property details with high-resolution images via Cloudinary
- **Edit Listings** - Modify existing property information and details
- **Delete Listings** - Remove properties with owner verification
- **Property Categories** - 8 diverse categories:
   | | | |
  |---|---|---|
  | 🔥 Trending | 🛏️ Rooms | 🏙️ Iconic Cities |
  | ⛰️ Mountains | 🏰 Castles | 🏊 Amazing Pools |
  | ⛺ Camping | 🐄 Farms |
-**Rich Property Details** - Title, description, location, price, images, and geographic coordinates
### 🔍 Search & Filtering
- **Location Search** - Find properties by city, country, or region (case-insensitive)
- **Category Filtering** - Filter by property types with visual icons
- **Explore Button** - Reset category filters and show all listings

### ⭐ Reviews & Ratings
- **User Reviews** - Authenticated users can leave detailed comments
- **Rating System** - Comprehensive 1-5 star rating functionality with visual stars
- **Review Management** - Delete your own reviews from profile page
- **Profile Integration** - All user reviews displayed on profile page


📁 Project Structure
```StayNest/
├── Models/                 # Database schemas
│   ├── listing.js          # Property listing schema
│   ├── review.js           # Review & rating schema
│   └── user.js             # User account schema
├── controllers/            # Business logic
│   ├── listings.js         # Listing operations
│   ├── reviews.js          # Review operations
│   ├── user.js             # User authentication
├── routes/                 # API endpoints
│   ├── listing.js          # Listing routes
│   ├── review.js           # Review routes
│   ├── user.js             # Auth routes
├── views/                  # EJS templates
│   ├── listings/           # Property listing pages
│   ├── users/              # User pages (login, signup, bookings)
│   ├── layouts/            # Layout templates
│   └── includes/           # Reusable components (navbar, footer)
├── public/                 # Static assets
│   ├── css/                # Stylesheets
│   ├── js/                 # Client-side scripts
│   │   └── script.js       # General scripts
├── utils/                  # Utility functions
│   ├── ExpressError.js     # Custom error class
│   └── wrapAsync.js        # Async error handler
├── init/                   # Database initialization
│   |── data.js             # Sample data
|   |__index.js
├── app.js                  # Main application file
├── middleware.js           # Custom middleware
├── schema.js               # JOI validation schemas
├── cloudConfig.js          # Cloudinary configuration
└── package.json            # Dependencies
```
## 📖 Usage

### For Guests
- **Browse Properties** - Visit homepage to explore all available listings
- **Search & Filter** - Use location search and category filters to find properties
- **View Details** - Click on any listing to see full information and reviews
- **Sign Up** - Create an account to access booking and wishlist features

### For Registered Users
- **Login** - Access your account with username and password
- **Leave Reviews** - Share your experience with ratings and comments
- **Search & Filter** - Use location search and category filters to find properties
- **Manage Profile** - View your reviews and profile information
- **Logout** - Securely exit when done

### For Hosts
- **Create Account** - Sign up to become a host
-  **Add Listings** - Click "Become a host" to add your property
- **Property Details** - Fill in title, description, location, price, and category
- **Upload Images** - Add high-quality photos of your property via Cloudinary
- **Publish Listing** - Make your property available for bookings
- **Manage Properties** - Edit or delete your listings as needed

## 👨‍💻 Author

**Biswarupa Baral**

