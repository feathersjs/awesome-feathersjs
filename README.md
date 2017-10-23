<p align="center">
  <br>
  <img width="400" src="./awesome-feathers.png" alt="logo of awesome-feathersjs repository">
  <br>
  <br>
</p>

# Awesome Feathers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome things related to FeathersJS

- [Resources](#resources)
  - [Official](#official-resources)
  - [Videos](#official-resources)
  - [Examples](#examples)
- [Projects Using Feathers](#projects-using-feathers)
- [Plugins](#plugins)
  - [Authentication and Authorization](#authentication-and-authorization)
  - [Caching](#caching)
  - [Database](#database)
  - [Documentation](#documentation)
  - [Email and SMS](#email-and-sms)
  - [Hooks](#hooks)
  - [Payments](#payments)
  - [Scaling](#scaling)
  - [Social media](#social-media)
  - [Testing](#testing)
  - [Transports](#transports)
  - [Utilities](#utilities)
  - [Validation](#validation)
- [Mobile Clients](#mobile-clients)
  - [iOS](#ios)
  - [Android](#android)
- [JS Clients](#js-clients)
  - [Framework Agnostic](#framework-agnostic)
  - [DoneJS](#donejs)
  - [React and Redux](#react-and-redux)
  - [Vue.js](#vue.js)
  - [Angular 1](#angular-1)
  - [Angular 2](#angular-2)
  - [Polymer](#polymer)
  - [AureliaJS](#aureliajs)
  - [Mithril](#mithril)


## Resources

### Official Resources

- [Docs](https://docs.feathersjs.com)
- [Website](https://feathersjs.com)
- [Guides](https://docs.feathersjs.com)
- [Slack](https://slack.feathersjs.com)

### Videos

- [The FeathersJS Youtube playlist](https://www.youtube.com/playlist?list=PLwSdIiqnDlf_lb5y1liQK2OW5daXYgKOe)
- [FeathersJS Real-Time Chat App - Tutorial](https://www.youtube.com/watch?v=CuM4vLkBaik)
- [Fullstack Feathersjs and React Web App](https://www.youtube.com/playlist?list=PLN3n1USn4xlnulnnBGD2RMid_p7xVj9xU)

### Examples

- [Feathers Chat](https://github.com/feathersjs/feathers-chat) ![Official Feathers Repo](/img/tiny-feathers-logo.png)
- [Feathers React Native Chat](https://github.com/feathersjs/feathers-react-native-chat) ![Official Feathers Repo](/img/tiny-feathers-logo.png)
- [Feathers-Vuex (Vue.js) Chat](https://github.com/feathersjs/feathers-chat-vuex) ![Official Feathers Repo](/img/tiny-feathers-logo.png)
- [Best Buy API Playground](https://github.com/BestBuy/api-playground)
- [Feathers + Quasar](https://github.com/claustres/quasar-feathers-tutorial)
- [Feathers + Apollo](https://github.com/swarthout/feathers-apollo)
- [Feathers 2 + Vue 2 + SSR + Email Verification](https://github.com/codingfriend1/Feathers-Vue)
- [Feathers 2 + Vue 2 + Email Verification + Cordova + Framework 7](https://github.com/codingfriend1/Feathers-Vue/tree/cordova)
- [Feathers + React + Mobx](https://github.com/foxhound87/rfx-stack)
- [Feathers + React + Webpack](https://github.com/sscaff1/feathers-webpack-react)
- [Observables with Angular2 and FeathersJS](https://berndsgn.ch/observables-with-angular-and-feathersjs/)
- [Feathers + React + Redux + Webpack + local auth. Production quality](https://github.com/eddyystop/feathers-starter-react-redux-login-roles).
- [Live query. Mirror part of a DB on the client.](https://github.com/eddyystop/feathers-live-query)
- [Feathers + React + Redux + Webpack + complete auth + offline mode (ideal for production)](https://github.com/bertho-zero/react-redux-universal-hot-example)
- [Build a CRUD App Using React, Redux and FeathersJS](https://www.sitepoint.com/crud-app-react-redux-feathersjs/)
- [feathers-nuxt](https://github.com/silvestreh/feathers-nuxt) - A sample/starter for server-side rendered Vue.js + Feathers applications that supports user authentication
- [Passwordless Auth Example Using feathers-authentication-management](https://github.com/rhythnic/feathers-passwordless-auth-example)

## Projects Using Feathers

- [BeachfrontDigital](https://beachfront.digital)
- [ContactImpact](https://www.contactimpact.de)
- [Equibit Group](https://equibitgroup.com/)
- [Foxflow](https://www.foxflow.com/)
- [GenerousTickets](https://generoustickets.com/)
- [Gratify](https://gratifyhq.com)
- [Headstart](http://www.headstartapp.com/)
- [HaulHound](https://haulhound.com/)
- [J.A.B. Property Investments](https://jabpi.com)
- [Koola](http://koola.io/)
- [Shakepay](https://shakepay.co)
- [Sleeker](https://sleeker.co)
- [Simpla](https://www.simpla.io/)
- [Stoplight](https://stoplight.io/)
- [Taxfyle](https://www.taxfyle.com/)
- [Work ID](http://work.id/)


## Plugins

### Authentication and Authorization

- [feathers-accounts](https://www.npmjs.com/package/feathers-accounts) - Token-Based User Account System for FeathersJS (configure).
- [feathers-authentication](../api/authentication/server.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-client](../api/authentication/client.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-local](../api/authentication/local.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-oauth1](../api/authentication/oauth1.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-oauth2](../api/authentication/oauth2.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-popups](https://github.com/feathersjs/feathers-authentication-popups) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-keystone](https://github.com/virtuozzo/feathers-authentication-keystone)
- [feathers-permissions](https://github.com/feathersjs/feathers-permissions) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-authentication-management](https://github.com/feathersjs/feathers-authentication-management) ![Official Feathers Repo](/img/tiny-feathers-logo.png) - User email verification and password reset capabilities to local feathers-authentication (service)
- [feathers-authentication-compatibility](https://www.npmjs.com/package/feathers-authentication-compatibility) - Keep `v0.x` clients compatible with `v1.0+` authentication

### Caching
- [feathers-hooks-rediscache](https://github.com/idealley/feathers-hooks-rediscache) - API endpoint caching with Redis.

### Database

- [amity-mongodb](https://www.npmjs.com/package/amity-mongodb) - Use various FeatherJS services to manage a MongoDB server with Amity.
- [feathers-blob](https://www.npmjs.com/package/feathers-blob) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Feathers abstract blob store service (service)
- [feathers-blueprints](https://www.npmjs.com/package/feathers-blueprints) - Add some of the Sails.js blueprints functionality to Feathers. (configure)
- [feathers-bookshelf](https://www.npmjs.com/package/feathers-bookshelf) - A bookshelf ORM service adapter.  (service)
- [feathers-couchdb](https://github.com/lontongcorp/feathers-couchdb)
- [feathers-dynamodb](https://github.com/jus101/feathers-dynamodb) - Work in progress - help wanted!
- [feathers-elasticsearch](https://github.com/feathersjs/feathers-elasticsearch) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-filemaker](https://www.npmjs.com/package/feathers-filemaker) - Filemaker adapter for feathers.js
- [feathers-knex](../api/databases/knexjs.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-levelup](https://www.npmjs.com/package/feathers-levelup)
- [feathers-linvodb](https://www.npmjs.com/package/feathers-linvodb) - Create an LinvoDB Service for FeatherJS. (service)
- [feathers-localstorage](../api/databases/localstorage.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-memory](../api/databases/memory.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-mongo-collections](https://www.npmjs.com/package/feathers-mongo-collections) - MongoDB collections service for FeathersJS. (service)
- [feathers-mongo-databases](https://www.npmjs.com/package/feathers-mongo-databases) - Create a MongoDB database service for FeathersJS. (service)
- [feathers-mongodb](../api/databases/mongodb.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-mongodb-revisions](https://www.npmjs.com/package/feathers-mongodb-revisions) - This Feathers database adapter extends the basic MongoDB adapter, adding revision support. (service)
- [feathers-mongoose](../api/databases/mongoose.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-nedb](../api/databases/nedb.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-nedb-dump](https://www.npmjs.com/package/feathers-nedb-dump) - Middleware for Feathers.js - dumps and restores NeDB database for a given service (middleware)
- [feathers-objection](https://github.com/mcchrish/feathers-objection) - A service adapter for [Objection.js](https://vincit.github.io/objection.js) - A minimal SQL ORM built on top of Knex.
- [feathers-orm-service](https://www.npmjs.com/package/feathers-orm-service) - Easily create an Object Relational Mapping Service for Featherjs.
- [feathers-rethinkdb](../api/databases/rethinkdb.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-rethinky](https://www.npmjs.com/package/feathers-rethinky) - Thinky.js RethinkDB Adaptor for Feathers JS
- [feathers-seeder](https://www.npmjs.com/package/feathers-seeder) - Straightforward data seeder for FeathersJS services.
- [feathers-sequelize](../api/databases/sequelize.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-skypager](https://www.npmjs.com/package/feathers-skypager) - A skypager ORM service adapter (service)
- [feathers-solr](https://www.npmjs.com/package/feathers-solr) - Solr Adapter for Feathersjs
- [feathers-waterline](https://www.npmjs.com/package/feathers-waterline)
- [nextql-feathers](https://github.com/giapnguyen74/nextql-feathers) - Featherjs plugin for NextQL-Yet Another Data Query Language. Equivalent GraphQL but much more simple


### Documentation

- [feathers-swagger](https://www.npmjs.com/package/feathers-swagger) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Add documentation to your Feathers services and feed them to Swagger UI. (configure)


### Email and SMS

- [feathers-mailer](https://www.npmjs.com/package/feathers-mailer) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Feathers mailer service using nodemailer (service)
- [feathers-mailgun](https://www.npmjs.com/package/feathers-mailgun) ![Official Feathers Module](/img/tiny-feathers-logo.png) - A Mailgun Service for FeatherJS. (service)
- [feathers-sendgrid](https://www.npmjs.com/package/feathers-sendgrid) ![Official Feathers Module](/img/tiny-feathers-logo.png) - A SendGrid Service for FeatherJS. (service)

### Hooks

- [hooks](https://www.npmjs.com/package/feathers-hooks-common) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Official collection of useful Feathers hooks.
- [feathers-hooks-csvtoarray](https://www.npmjs.com/package/feathers-hooks-csvtoarray) - Feathers hook for converting a comma-delimited list to an Array of strings.
- [feathers-hooks-jsonapify](https://www.npmjs.com/package/feathers-hooks-jsonapify) - Feathers hook for outputting data in a JSON-API-compliant way.
- [feathers-populate-hook](https://www.npmjs.com/package/feathers-populate-hook) - Feathers hook to populate multiple fields with n:m, n:1 or 1:m relations. (hook)
- [feathers-transform-hook](https://www.npmjs.com/package/feathers-transform-hook) - Feathers hook for transform hook.data parameters (hook)
- [feathers-virtual-attribute-hook](https://www.npmjs.com/package/feathers-virtual-attribute-hook) - Feathers hook for add virtual attributes to your service response (hook)

### Payments

- [feathers-stripe](https://github.com/feathersjs/feathers-stripe) ![Official Feathers Module](/img/tiny-feathers-logo.png)

### Scaling

- [mostly-feathers](https://github.com/MostlyJS/mostly-feathers) - Convert your Feathers APIs into microservices
- [mostly-feathers-rest](https://github.com/MostlyJS/mostly-feathers-rest) - Expose your microservice as a RESTful API
- [feathers-cluster](https://www.npmjs.com/package/feathers-cluster) - Easily take advantage of multi-core systems for Feathers. (configure)
- [feathers-sync](https://www.npmjs.com/package/feathers-sync) ![Official Feathers Module](/img/tiny-feathers-logo.png)  - Synchronize service events between application instances using MongoDB publish/subscribe (configure)
- [feathers-batch](https://github.com/feathersjs/feathers-batch/) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Batch multiple Feathers service calls into one (service)

### Social media

- [feathers-services-instagram-feed](https://www.npmjs.com/package/feathers-services-instagram-feed) - A service that allows to fetch a given user's Instagram feed via its public endpoints.

### Testing

- [feathers-tests-fake-app-users](https://www.npmjs.com/package/feathers-tests-fake-app-users) - Fake some feathers dependencies in service unit tests. Starter for your customized fakes (service)

### Transports

- [feathers-primus](../api/primus.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-rest](../api/rest.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-socketio](../api/socketio.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-batch](https://www.npmjs.com/package/feathers-batch) - Batch multiple Feathers service calls into one (service)
- [feathers-socketcluster](https://github.com/polst/feathers-socketcluster) - Use SocketCluster for client/server communication. Not published.


### Utilities

- [feathers-bootstrap](https://github.com/feathersjs/feathers-bootstrap) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-cli](https://github.com/feathersjs/feathers-cli) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-client](../api/client.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-commons](https://github.com/feathersjs/feathers-cli) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-configuration](../guides/advanced/configuration.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-errors](../api/errors.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-fs](https://github.com/feathersjs/feathers-fs) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Use the FeathersJS service interface to read and write data in the file system.
- [feathers-generator](https://github.com/feathersjs/feathers-generator) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-hooks](../api/hooks.md) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-hooks-common](../api/hooks-common.md) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Useful hooks for use with Feathersjs services. (hooks)
- [feathers-hooks-utils](https://www.npmjs.com/package/feathers-hooks-utils) - Utility library for writing Feathersjs hooks. (hooks)
- [feathers-logger](https://github.com/feathersjs/feathers-logger) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-query-filters](https://github.com/feathersjs/feathers-query-filters) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-profiler](https://github.com/feathersjs/feathers-profiler) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-socket-commons](https://github.com/feathersjs/feathers-socket-commons) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [generator-feathers](https://github.com/feathersjs/generator-feathers) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [generator-feathers-plugin](https://github.com/feathersjs/generator-feathers-plugin) ![Official Feathers Module](/img/tiny-feathers-logo.png)
- [feathers-versionate](https://github.com/luke3butler/feathers-versionate) - Utility for creating and working with nested service paths.


### Validation

- [feathers-hooks-validate-joi](https://www.npmjs.com/package/feathers-hooks-validate-joi) - Feathers hook utility for schema validation, sanitization and client notification using Joi. (hook)
- [feathers-hook-validation-jsonschema](https://www.npmjs.com/package/feathers-hook-validation-jsonschema) - Validate Feathers resources using JSON Schema. (hook)
- [feathers-tcomb](https://www.npmjs.com/package/feathers-tcomb) - validate feathers services using tcomb (app.service)
- [feathers-validate-hook](https://www.npmjs.com/package/feathers-validate-hook) - Feathers hook for validate json-schema with is-my-json-valid (hook)
- [feathers-validator](https://www.npmjs.com/package/feathers-validator) - A validator for Feathers services. (service)

## Mobile Clients

The Feathers client works with React Native but here is a collection of native libraries/SDKs.

## iOS

- [FeathersjsClientSwift](https://github.com/truebucha/FeathersjsClientSwift) - An iOS client written in Swift.
- [Feathers](https://github.com/startupthekid/feathers-ios) - Feathers compliant SDK written in Swift 3. Supports rest and socket providers.

## Android

- [feathers-android](https://github.com/feathersjs-ecosystem/feathers-android) - An Android client.

## JS Clients

### Framework Agnostic

- [feathers-client](https://www.npmjs.com/package/feathers-client) ![Official Feathers Module](/img/tiny-feathers-logo.png) - All of the main client packages rolled into one.
- [feathers-reactive](https://www.npmjs.com/package/feathers-reactive) ![Official Feathers Module](/img/tiny-feathers-logo.png) - Turns a Feathers service call into an RxJS observables that automatically updates on real-time events. (configure)

### DoneJS

- [can-connect-feathers](https://www.npmjs.com/package/can-connect-feathers) - Feathers client library for DoneJS (feathers-client)
- [canjs-feathers](https://www.npmjs.com/package/canjs-feathers) - CanJS model implementation that connects to Feathers services through feathers-client. (feathers-client)
- [donejs-feathers](https://www.npmjs.com/package/donejs-feathers) - A generator to quickly add FeathersJS to your DoneJS project. Includes Auth! (generator)

### React and Redux

- [feathers-action](https://www.npmjs.com/package/feathers-action) - use feathers services with redux (connector)
- [feathers-action-creators](https://www.npmjs.com/package/feathers-action-creators) - redux action creators for feathers services
- [feathers-action-reducer](https://www.npmjs.com/package/feathers-action-reducer) - redux reducer for feathers service actions
- [feathers-action-types](https://www.npmjs.com/package/feathers-action-types) - flux action types for feathers services (connector)
- [feathers-react-redux](https://www.npmjs.com/package/feathers-react-redux) - Unofficial Feathers bindings for React-Redux.
- [feathers-reduxify-services](https://github.com/eddyystop/feathers-reduxify-services) - Wrap Feathers services so they work transparently and perfectly with Redux.
- [feathers-reduxify-authentication](https://github.com/eddyystop/feathers-reduxify-authentication) - Wrap Feathers.authentication so it works with Redux, and with auth packages for React-Router.

### Vue.js

- [feathers-vuex](https://github.com/feathersjs/feathers-vuex) ![Official Feathers Module](/img/tiny-feathers-logo.png)  - Integration of Feathers services with your Vuex store.
- [vue-syncers-feathers](https://www.npmjs.com/package/vue-syncers-feathers) - Synchronises feathers services with vue objects, updated in real time (connector)
- [vue-feathers](https://github.com/sunabozu/vue-feathers) - A plugin for Vuejs 1.x & 2.x to easily access your feathers services.

### Angular 1

- [ng-feathers](https://www.npmjs.com/package/ng-feathers) - Feathers client for AngularJS. FeatherJS for plain old AngularJS (1.X)

### Angular 2

Submit yours!

### Polymer

- [feathers-polymer](https://github.com/thosakwe/polymer-feathers)

### AureliaJS

- [aurelia-feathersjs-socket-demo](https://bitbucket.org/praveengandhi/aurelia-feathersjs-socket-demo) - Aurelia app (built with Aurelia-CLI) connected to Feathers server application via websockets (socket.io)

### Mithril

- [feathers-mithril](https://www.npmjs.com/package/feathers-mithril) - Connect feathers.js to mithril.js (connector)
