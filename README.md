# NETLIFY PORTFOLIO WEBPAGE

This is a personal website built with Next.js, TypeScript, and Tailwind CSS. The site includes various sections such as a project feed, quotes, and blog posts.

[![Netlify Status](https://api.netlify.com/api/v1/badges/df96a8a5-6432-441c-98af-6f2e7488ef1c/deploy-status)](https://app.netlify.com/sites/sulaiman-niazi/deploys)

## Project Structure

The project has the following structure:

## Key Features

- **Project Feed**: Displays a list of projects with various layouts.
- **Quote Section**: Displays quotes with author information.
- **Blog Posts**: Displays a list of blog posts sorted by date.

## Components

### ProjectFeedLayout

Located in [`src/components/layouts/ProjectFeedLayout/index.tsx`](src/components/layouts/ProjectFeedLayout/index.tsx), this component is responsible for rendering the project feed layout.

### ProjectFeedSection

Located in [`src/components/sections/ProjectFeedSection/index.tsx`](src/components/sections/ProjectFeedSection/index.tsx), this component handles the display of project feed sections with different variants.

### QuoteSection

Located in [`src/components/sections/QuoteSection/index.tsx`](src/components/sections/QuoteSection/index.tsx), this component displays quotes with optional author information.

## Utilities

### Static Props Resolvers

Located in [`src/utils/static-props-resolvers.ts`](src/utils/static-props-resolvers.ts), this file contains functions to fetch and sort content objects such as posts and projects.

### Highlighted Markdown

Located in [`src/utils/highlighted-markdown.tsx`](src/utils/highlighted-markdown.tsx), this file provides a custom component for rendering highlighted code blocks in markdown content.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/SulaimanNiazi/NETLIFY_PORTFOLIO_WEBPAGE.git
    ```
2. Navigate to the project directory:
    ```sh
    cd personal-site
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

### Development

To start the development server, run:
```sh
npm run dev
```

### Build

To build the project, run:
```sh
npm run build
```

### Start

To start the production server, run:
```sh
npm start
```

## License

This project is licensed under the MIT License.
```

Feel free to customize this README to better fit your project's specifics.
Feel free to customize this README to better fit your project's specifics.