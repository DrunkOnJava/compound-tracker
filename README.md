# Compound Tracker

A comprehensive web application for tracking compound administrations and visualizing their levels over time using Chart.js.

## Features

### Core Features
- Add and track compound administrations with precise dosage and timing
- Visualize compound levels over time with interactive charts
- Mobile-responsive design for tracking on any device
- Local storage persistence for offline access
- Real-time updates and calculations
- Pinned administration form for quick access
- Multiple profile support for different tracking needs

### User Interface
- Clean, intuitive interface with dark/light mode support
- Interactive charts with zoom and pan capabilities
- Detailed compound information and reference guides
- Comprehensive administration log with filtering options
- Quick-access administration form pinned to the upper left

### Data Management
- Secure local storage for privacy
- Export/import functionality for data backup
- Detailed logging of all administrations
- Multiple compound categories and classifications

## Getting Started

### Development Setup

1. Clone the repository:
```bash
git clone https://github.com/[username]/compound-tracker.git
cd compound-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm start
```

The application will be available at http://localhost:3000

### Docker Setup

For Docker users:
```bash
docker-compose up
```

## Deployment

To deploy to GitHub Pages:

1. Update the `homepage` field in `package.json` with your GitHub username:
```json
{
  "homepage": "https://[username].github.io/compound-tracker"
}
```

2. Deploy:
```bash
npm run deploy
```

## Available Scripts

- `npm start` - Start development server
- `npm test` - Run test suite
- `npm run deploy` - Deploy to GitHub Pages
- `npm run format` - Format code with Prettier
- `npm run lint` - Lint JavaScript files
- `npm run build` - Build production version

## Project Structure

```
compound-tracker/
├── src/
│   ├── components/     # Reusable UI components
│   ├── js/
│   │   ├── data/      # Data models and storage
│   │   ├── managers/  # Business logic managers
│   │   └── utils/     # Utility functions
│   ├── css/           # Styling files
│   └── index.html     # Main entry point
├── server/            # Backend server (if applicable)
└── docker/            # Docker configuration
```

## Technologies Used

- HTML5/CSS3 for structure and styling
- JavaScript (ES6+) for application logic
- Chart.js for data visualization
- Luxon for date/time handling
- Docker for containerization
- GitHub Pages for deployment

## Future Implementations

- Enhanced data visualization with multiple chart types
- Advanced compound interaction tracking
- Customizable alerts and reminders
- Data export in multiple formats
- Advanced filtering and search capabilities
- API integration for compound information
- Progressive Web App (PWA) support
- Offline-first architecture
- Multi-language support

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
