
# Gallery App

A minimal React + Vite gallery application using Tailwind CSS. This repository is a small starter app that displays images in a responsive card layout and demonstrates a simple React component structure.

## Quick overview

- Frameworks: React 19 + Vite
- Styling: Tailwind CSS
- Linting: ESLint

## Features

- Responsive gallery layout with reusable `Card` component (`src/components/card.jsx`).
- Fast refresh during development via Vite.
- Ready-to-use scripts for development, build and preview.

## Requirements

- Node.js 16+ recommended
- npm (or yarn / pnpm)

## Setup

1. Clone the repository:

	 git clone <repo-url>
	 cd Gallery-App

2. Install dependencies:

	 npm install

3. Start development server:

	 npm run dev

Open http://localhost:5173 in your browser.

## Available scripts

- `npm run dev` — Starts the Vite development server (with HMR)
- `npm run build` — Builds production assets into `dist/`
- `npm run preview` — Serves the production build locally for a quick check
- `npm run lint` — Runs ESLint across the project

## Project structure

```
Gallery-App/
	src/
		App.jsx         # Main application component
		main.jsx        # React DOM mount point
		components/
			card.jsx      # Image card component
		assets/         # Static assets used by the app
	public/           # Static files served at root
	index.html
	package.json
	vite.config.js
	README.md
```

## Notes & customization

- Tailwind is included as a dependency. If you want to customize the design, update the Tailwind config (not included in this minimal template) or add it to the project.
- If you add TypeScript later, update ESLint and install the necessary types.

## Contributing

Feel free to open issues or submit pull requests. Small, focused PRs with a short description are easiest to review.

## License

Add your preferred license (e.g. MIT) or remove this section if not applicable.

---

If you'd like, I can:

- Add a short usage section showing how to add images to the gallery
- Add a Tailwind configuration file and basic utilities
- Convert components to TypeScript

Tell me which of those you'd like next.
