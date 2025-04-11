

## Project setup
Before running the `yarn dev` or `yarn build` script, you need to create the `getPassKey.js` file in the `src/utils` directory.  Inside the file write

```js
export default function() {
  return 'anything-you-want';
}
```

```bash
# Install dependencies
pnpm install

# Compiles and hot-reloads for development for the chrome browser
pnpm dev

# Compiles and minifies for production for the chrome browser
pnpm build

# Create a zip file from the build folder
pnpm build:zip

# Compiles and hot-reloads for development for the firefox browser
pnpm dev:firefox

# Compiles and minifies for production for the firefox browser
pnpm build:firefox

# Lints and fixes files
pnpm lint
```
