# Lewis Family History

An interactive website documenting seven generations of the Lewis family in Tallahassee, Florida, from Benjamin Cheever Lewis's arrival in 1836 to the present day.

## Features

- Interactive family tree visualization
- Timeline of family milestones
- Migration map showing family movements
- Photo galleries
- Notable family members and achievements
- Properties and legacy information

## Getting Started

### Prerequisites

- Node.js (version 14 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Benny9193/family.git
cd family
```

2. Install dependencies:
```bash
npm install
```

### Development

To start a local development server:

```bash
npm start
```

This will open the website in your default browser at `http://localhost:8080`.

For development with live reload (manual refresh needed):

```bash
npm run dev
```

### Building

To validate and prepare the project for deployment:

```bash
npm run build
```

This will:
- Validate all JavaScript files
- Check for syntax errors
- Confirm the project is ready for deployment

### Code Quality

#### Linting

Lint JavaScript files:
```bash
npm run lint:js
```

Lint CSS files:
```bash
npm run lint:css
```

Lint all files:
```bash
npm run lint
```

#### Testing

Run validation tests:
```bash
npm test
```

## Project Structure

```
.
├── index.html           # Main HTML file
├── style.css            # Stylesheet
├── app.js               # Main JavaScript application
├── app_1.js             # Alternative JavaScript version
├── app_enhanced.js      # Enhanced JavaScript version
├── package.json         # Project dependencies and scripts
├── .eslintrc.json       # ESLint configuration
├── .stylelintrc.json    # Stylelint configuration
└── README.md            # This file
```

## Deployment

The website is a static site and can be deployed to any static hosting service:

- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Azure Static Web Apps

Simply deploy the following files:
- `index.html`
- `style.css`
- `app.js` (or your preferred JS version)

## License

ISC