# @angular-redux/store

Angular bindings for [Redux](https://github.com/reactjs/redux).

For Angular 1 see [ng-redux](https://github.com/wbuchwalter/ng-redux)

[![Join the chat at https://gitter.im/angular-redux/ng2-redux](https://badges.gitter.im/angular-redux/ng2-redux.svg)](https://gitter.im/angular-redux/ng2-redux?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![CircleCI](https://img.shields.io/circleci/project/github/angular-redux/store.svg)](https://github.com/angular-redux/store)
[![npm version](https://img.shields.io/npm/v/@angular-redux/store.svg)](https://www.npmjs.com/package/@angular-redux/store)

## What is Redux?

Redux is a popular approach to managing state in applications. It emphasises:

* A single, immutable data store.
* One-way data flow.
* An approach to change based on pure functions and a stream of actions.

You can find lots of excellent documentation here: [Redux](http://redux.js.org/).

## What is @angular-redux?

We provide a set of npm packages that help you integrate your redux store
into your Angular 2+ applications. Our approach helps you by bridging the gap
with some of Angular's advanced features, including:

* Change processing with RxJS observables.
* Compile time optimizations with `NgModule` and Ahead-of-Time compilation.
* Integration with the Angular change detector.

## Getting Started

* I already know what Redux and RxJS are. [Give me the TL;DR](docs/quickstart.md).
* I'm just learning about Redux. [Break it down for me](docs/intro-tutorial.md)!
* Talk is cheap. [Show me a complete code example](https://github.com/angular-redux/example-app).
* Take me to the [API docs](docs/api.md).

## Examples

Here are some examples of the `angular-redux` family of packages in action:

* [Zoo Animals Combined Example App](https://github.com/angular-redux/example-app)
* [Simple SystemJS Example (Angular Quickstart)](https://github.com/angular-redux/system-js-example)

## Companion Packages

* [Reduxify your Routing with @angular-redux/router](https://github.com/angular-redux/router)
* [Reduxify your Forms with @angular-redux/form](https://github.com/angular-redux/form)

## Resources

* [Using Redux with Angular - JS Toronto Meetup 2016-07-12](https://www.youtube.com/watch?v=s4xr2avwv3s)
* [Angular and Redux from Rangle.io](http://ngcourse.rangle.io/handout/redux/)
* [Getting started with Redux](https://egghead.io/courses/getting-started-with-redux)
* [Awesome Redux: Community Resources](https://github.com/xgrommx/awesome-redux)

## In-Depth Usage

`@angular-redux/store` uses an approach to redux based on RxJS Observables to `select` and transform
data on its way out of the store and into your UI or side-effect handlers. Observables
are an efficient analogue to `reselect` for the RxJS-heavy Angular world.

Read more here: [Select Pattern](docs/select-pattern.md)

We also have a number of 'cookbooks' for specific Angular topics:

* [Using Angular's Dependency Injector with Action Creators](docs/action-creator-service.md)
* [Using Angular's Dependency Injector with Middlewares](docs/di-middleware.md)
* [Managing Side-Effects with redux-observable Epics](docs/epics.md)
* [Using the Redux DevTools Chrome Extension](docs/redux-dev-tools.md)
* [@angular-redux/store and ImmutableJS](docs/immutable-js.md)
* [Strongly Typed Reducers](docs/strongly-typed-reducers.md)
