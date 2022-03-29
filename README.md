## Getting Started

Copy .env.sample to .env file
Set Proper API_URL

Install dependencies

```bash
npm install
# or
yarn install
```

To run the development server:

```bash
npm run dev
# or
yarn dev
```

# Brief

In order to get related people based on search query we query all resourses search endpoints and get all required people data.
Instead of doing this in client side we do it on serverside using next.js api feature
and properly format required data and show it to users on frontend. This is required as it would need a lot of http calls to the api server if done exclusively on client side.

# Scaling

We will need to cache required data or even index required data in search system like elastisearch which will help us in properly querying required data as there seems to be no single search endpoint for all required data in swapi api.
