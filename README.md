# Express Backend Boilerplate

A minimalist Express.js backend boilerplate with a clean architecture.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
```

2. Install dependencies:

```bash
npm install
```

## Usage

Start the development server:

```bash
npm run dev
```

Start in production mode:

```bash
npm start
```

## Project Structure

```
express-backend/
├── src/
│   ├── controllers/    # Request handlers
│   ├── routes/         # API routes
│   ├── models/         # Data models
│   └── middleware/     # Custom middleware
├── config/            # Configuration files
└── tests/            # Test files
```

## API Endpoints

- `GET /api/health` - Health check endpoint
- Additional endpoints will be documented here

## License

MIT
