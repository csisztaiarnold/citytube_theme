# The frontend for the CityTube Drupal 8 module.

A React frontend for the CityTube module (https://github.com/csisztaiarnold/citytube).

## Installing

Have a Drupal 8 installation, `node` and `npm` set up.

Install and enable the [CityTube Drupal 8 module](https://github.com/csisztaiarnold/citytube).

Import a few videos.

Install the JSON:API and CORS modules for enabling cross-origin resource sharing. Both come with Drupal core.

Create an `.env.local` from `.env.local.example` and set the environment variables (the API endpoints).

```
npm install
```

```
npm start
```

Go to http://localhost:3000