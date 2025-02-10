# Restaurant List Application

A full-stack web application for managing and starring your favorite restaurants. Built with React, Express, and Node.js.

## Features

- View a list of restaurants
- Star/unstar restaurants
- Add comments to starred restaurants
- Update comments for starred restaurants
- Delete restaurants from your starred list
- View detailed information about each restaurant

## Tech Stack

### Backend
- Node.js
- Express.js
- UUID for unique identifiers
- Express Router for API routing

### Frontend
- React
- React Router for navigation
- Modern JavaScript (ES6+)
- CSS for styling

## API Endpoints

### Restaurants
- `GET /restaurants` - Get all restaurants
- `GET /restaurants/:id` - Get a specific restaurant

### Starred Restaurants
- `GET /starred-restaurants` - Get all starred restaurants
- `GET /starred-restaurants/:id` - Get a specific starred restaurant
- `POST /starred-restaurants` - Add a restaurant to starred list
- `DELETE /starred-restaurants/:id` - Remove a restaurant from starred list
- `PUT /starred-restaurants/:id` - Update a starred restaurant's comment

## Project Structure

```
.
├── backend/
│   ├── routes/
│   │   ├── restaurants.js
│   │   └── starredRestaurants.js
│   ├── app.js
│   └── package.json
└── frontend/
    ├── src/
    │   ├── api/
    │   ├── components/
    │   └── App.js
    └── package.json
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/YFolla/restaurantlist.git
cd restaurantlist
```

2. Install dependencies:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Start the servers:
```bash
# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 