# Installation

1. Creating react-app with vite [https://vitejs.dev/guide/](https://vitejs.dev/guide/)

- `npm create vite@latest my-react-app --template react`
- my-react-app is the name of the app
- the above command is for using react template with vite

2. Using Tailwind CSS [https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation)

- `npm install -D tailwindcss`
- initialize it with `npx tailwindcss init`

3. Install other react old packages using legacy word:

`npm install --legacy-peer-deps @react-three/fiber @react-three/drei maath react-tilt react-vertical-timeline-component @emailjs/browser framer-motion react-router-dom`

- "**--legacy-peer-deps**" is a message that tells npm to use an older way of handling dependencies, because the package you're trying to install might not have been updated to use the new way yet.

- In the above command we are installing below ones in one go:
- **@react-three/fiber** -> A React renderer for Threejs. [https://www.npmjs.com/package/react-three-fiber](https://www.npmjs.com/package/react-three-fiber) and [https://docs.pmnd.rs/react-three-fiber/getting-started/introduction](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- **@react-three/drei** -> A growing collection of useful helpers and fully functional, ready-made abstractions for @react-three/fiber.
- **maath** -> Math utility functions whe working with threejs we will use some calculations
- **react-tilt** -> provides cool animation when hovering over cards
- **react-vertical-timeline-component** -> for the experience similiar to the linkedin
- **@emailjs/browser** -> EmailJS helps to send emails using client-side technologies only. No server is required – just connect EmailJS to one of the supported email services, create an email template, and use our SDK to trigger an email.[https://www.npmjs.com/package/@emailjs/browser](https://www.npmjs.com/package/@emailjs/browser)
- **framer-motion** ->Framer Motion is an open source, production-ready library that’s designed for all creative developers.Framer Motion is a simple yet powerful motion library for React.
  It powers the amazing animations and interactions in Framer, the web builder for creative pros. Zero code, maximum speed.[https://www.framer.com/motion/introduction/](https://www.framer.com/motion/introduction/)
- **react-router-dom**

# Run the application

1. Run the application using `npm run dev`
