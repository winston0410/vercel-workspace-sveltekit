# Reproducing issue where SvelteKit cannot deploy with NPM workspace on Vercel

## Steps to build

Run all these in root:

```sh
npm install

npm run build:vercel

```

At the end the deploy should be successful, but we will see 404 in Vercel page.
