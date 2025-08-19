# fox9.de 🦊 11ty

[![Netlify Status](https://api.netlify.com/api/v1/badges/08d237c2-f7c1-42a5-a6a6-d88aa36965dc/deploy-status)](https://app.netlify.com/projects/fox9/deploys)

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

## UI Features

- Responsive layout with Bootstrap 5 integration
- Compact header with warm gradient background
- Side-by-side content layout on larger screens
- Cards with equal height in the same row
- Smooth animations and hover effects

## License

There is no license! This project is so private, even the foxes don’t know about it. But honestly, if you want to use or reuse anything here, go wild—just don’t blame me if your code starts acting foxy.
