# Roamora

A React learning project for an adventure travel landing page, with reusable navigation, destination cards, a footer, and separate service, product, and sign-up routes.

## What is implemented

- Landing page hero and destination card layout.
- Reusable buttons, navigation, cards, and footer components.
- Client-side routes at `/`, `/services`, `/products`, and `/sign-up`.

The service, product, and sign-up pages are placeholders. The hero references `/videos/video-1.mp4`, but that file is not included. There is no booking or account backend.

## Stack

React 17, JavaScript, CSS, React Router 5, and Create React App (`react-scripts` 4).

## Run locally

```bash
git clone https://github.com/okikioriola1/roamora.git
cd roamora
npm ci
npm start
```

Open the URL printed by the development server. No environment variables are required. This legacy build setup does not pin a Node.js version; compatibility with current Node/npm releases has not been verified.

## Scripts

- `npm start`: development server.
- `npm run build`: production bundle in `build/`.
- `npm test`: inherited test runner; no test files are currently included.

## Code map

- `src/App.js`: routes.
- `src/components/pages/`: route components.
- `src/components/`: navigation, hero, cards, buttons, and footer.
- `src/images/`: destination and page imagery.

## Next improvements

Replace the missing video with an appropriately licensed asset or a static hero, complete the placeholder pages, modernize the build tooling, and add navigation and sign-up tests as those flows are completed.
