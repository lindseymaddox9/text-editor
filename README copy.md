MINI PROJECT PWA-Deploy  Directory App on Render with Script

In this mini-project, you are given a simple application that needs to be updated to use webpack, service workers, and IndexedDB. In addition, it must have PWA functionality in order to work properly. Once you have updated the application with these new features, you will deploy it to Render. Render is not new to you, but you will need to add a handful of special scripts so that it knows to deploy your bundled application.


 I want to be able to install the web application as a PWA.

I want to be able to add and remove my contact cards.

I want all my scripts to run from the root directory `package.json`.

I want to be able to run `npm run start:dev` in the command line and have both my client and server start.

I want to be able to run `npm run start` in the command line to run our build script and start our server.

I want to be able to run `npm run server` in the command line and have just our server start without the client.

 I want to be able to run `npm run build` in the command line and have our client run the webpack build script.

 I want to be able to run `npm run install` in the command line and have all of the client's dependencies installed.

 I want to be able to run `npm run client` in the command line and have just our client start without the server.

## Acceptance Criteria

The mini-project is complete when the following criteria are met:

* The application uses webpack for bundling.

* The application uses a service worker to cache static assets.

* The application uses IndexedDB GET, ADD, and DELETE methods.

* The application uses object store for async/await.

* The application uses CSS loaders.

* Scripts are placed in the root and client directory's `package.json`.

* `npm run start:dev` starts both the client and server.

* `npm run start` runs the `build` script and starts the server.

* `npm run server` starts just the server and not the client.

* `npm run build` runs the webpack build script in the client.

* `npm run install` installs the dependencies for the client.

* `npm run client` starts the client without the server.

* The web application can be installed from the web address provided by Render.

* The web application is deployed using Render.

