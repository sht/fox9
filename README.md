# fox9.de 11ty

This repository contains the 11ty based website for [fox9.de](https://fox9.de), a private email domain.

## Overview

This is a simple website built with Eleventy to display information about the private domain fox9.de. The site is not intended for public consumption and is primarily used as a landing page for a private email domain.

## Project Structure

- `.eleventy.js` - Eleventy configuration file
- `src/` - Source files
- `_layouts/` - HTML layouts for the site
- `_includes/` - Reusable HTML components
- `_site/` - Generated site files (not committed)

## Development Setup

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone this repository

2. Navigate to the repository directory:
   ```
   cd path/to/repository
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the development server:
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:8080`

## Deployment

This site is set up to be deployed on Netlify. The `netlify.toml` file contains all necessary configuration for deployment.

To deploy manually:

```
npm run build
```

The built site will be in the `_site` directory, which can then be uploaded to your hosting provider.

## Customization

- Edit files in `src/` to change content
- Modify files in `_layouts/` and `_includes/` to change the site structure
- Add custom styles to files in `src/assets/css/`

## License

This project is private and not licensed for public use or distribution.
