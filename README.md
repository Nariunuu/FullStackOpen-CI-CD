# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full Stack Open course

Deployed app: https://fullstackopen-ci-cd-u897.onrender.com

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build
`npm run test:e2e` to run end-to-end tests with Playwright

## Exercise 21. Your own pipeline

Repository: https://github.com/Nariunuu/FullStackOpen-NextJS

The pipeline runs on every push and pull request to `main`. It installs
dependencies, lints, builds the Next.js app, and then runs a Playwright
end-to-end test suite against the built app.
