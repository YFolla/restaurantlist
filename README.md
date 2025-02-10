# Restaurant List Application

A full-stack application for managing restaurant lists with starring capabilities.

## Features

- View list of restaurants
- Add new restaurants
- Delete restaurants
- Update restaurant names
- Star/unstar restaurants
- Persistent storage

## Tech Stack

### Frontend
- React
- Redux for state management
- Modern UI components
- Fetch API for backend communication

### Backend
- Express.js
- RESTful API endpoints
- Supabase for data storage

## API Endpoints

- `GET /restaurants` - Get all restaurants
- `POST /restaurants` - Add a new restaurant
- `DELETE /restaurants/:id` - Delete a restaurant
- `PUT /restaurants/:id` - Update restaurant name
- `POST /restaurants/starred` - Star a restaurant

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/YFolla/restaurantlist.git
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
# Start backend server
cd backend
npm start

# Start frontend development server
cd frontend
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. 