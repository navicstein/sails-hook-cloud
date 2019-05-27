# sails-hook-cloud

Restify your actions in one place

routes are generated automatically

create `config/cloud.js` file

```js
module.exports.cloud = {
  proxy: "/api/v1/anything-at-all",
};
```

> This hook tends to generate automatic routes from your controllers/actions and binds them to sails without you manually creating them in the `config/routes.js`

visit http://locahost:1337/__cloud to view your actions in an explorer (you should have internet connection for the first time)

# Usage

- clone this project and copy the contents to your `api/hooks` folder or place it in your `node_modules` folder (sails can pick it up here)

i have plans to release this lib on npm.

> this project and solo was made fast in one day and so the readme too, this is just an experiment and proof
