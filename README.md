# Express + React/Vue Turborepo Starter

This is a minimal setup for a Turborepo monorepo using Express + React and/or Vue.

The React and Vue portions are trivial to set up, so if you don't like the configuration, you can simply delete the folder and reinstall with `npm create vite@latest` for React or `npm vue@latest` for Vue. TailwindCSS has been added to both React and Vue.

The Express server is configured with Typescript and Vite for hot reloading (on the backend side only, you still need to refresh your browser to see changes).

Syncpack is installed in the top-level directory. You can synchronize package versions across all your apps by running `npx syncpack fix-mismatches`.
