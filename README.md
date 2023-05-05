# Awesome Sanic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [Sanic](https://sanicframework.org/) resources and extensions  
> Sanic is an Async Python 3.7+ web server that's written to go fast

[User Guide](https://sanic.dev/) | [API Docs](https://sanic.readthedocs.io/) | [Source](https://github.com/sanic-org/sanic) | [Forums](https://community.sanicframework.org/) | [Discord](https://discord.gg/FARQzAEMAA)


## Contents
- [Awesome Sanic ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-sanic-)
  - [Contents](#contents)
  - [Extensions](#extensions)
    - [Official](#official)
    - [API](#api)
    - [Authentication](#authentication)
    - [Development](#development)
    - [Frontend](#frontend)
    - [Monitoring](#monitoring)
    - [ORM](#orm)
    - [Requests and Responses](#requests-and-responses)
    - [Caching](#caching)
    - [Tracing](#tracing)
    - [Queues](#queues)
    - [Scaffolding](#scaffolding)
    - [Session](#session)
    - [Utils](#utils)
  - [Resources](#resources)
    - [Examples](#examples)
    - [Tutorials](#tutorials)
    - [Books](#books)
    - [Videos and Podcasts](#videos-and-podcasts)
    - [Built with Sanic](#built-with-sanic)


## Extensions

### Official
- [Sanic Extensions](https://github.com/sanic-org/sanic-ext): Extended Sanic functionality
- [Sanic Testing](https://github.com/sanic-org/sanic-testing): Test clients
- [Sanic Docker](https://hub.docker.com/r/sanicframework/sanic): Docker images
- [Sanic Assets](https://github.com/sanic-org/sanic-assets): Official logo

### API
- [Sanic CRUD](https://github.com/Typhon66/sanic_crud): CRUD REST API generation with peewee models.
- [Sanic-GraphQL](https://github.com/graphql-python/sanic-graphql): GraphQL integration with Sanic
- [Sanic-RestPlus](https://github.com/ashleysommer/sanic-restplus): A port of Flask-RestPlus for Sanic. Full-featured REST API with SwaggerUI generation.
- [Sanic-Transmute](https://github.com/yunstanford/sanic-transmute): A Sanic extension that generates APIs from python function and classes, and also generates Swagger UI/documentation automatically.
- [Sanic-OpenAPI3e](https://github.com/endafarrell/sanic-openapi3e): A Sanic extension that allows you to decorate your routes and configure your OpenAPI spec v3.0 and swagger. Very high spec compliance, customisable.
- [Sanic-REST-Framework](https://github.com/Tioit-Wang/sanic-rest-framework): API rapid development framework for SANIC, Inspired by Django REST Framework, Has complete authority verification, authentication, serializer components, CBV suite, Depends on the tortoise ORM, Used together with srf_app_helper and tortoise-orm, You can get a smooth development experience like Django

### Authentication
- [Sanic-JWT](https://github.com/ahopkins/sanic-jwt): Authentication extension for JSON Web Tokens (JWT).
- [Sanic-JWT-Extended](https://github.com/NovemberOscar/Sanic-JWT-Extended): Port of flask-jwt-extended, provides access/refresh token with fresh, easy custom claim insertion, and role-based access control
- [Sanic-OAuth](https://gitlab.com/SirEdvin/sanic-oauth): OAuth Library with many provider and OAuth1/OAuth2 support.
- [Sanic-Token-Auth](https://github.com/saabeilin/sanic-token-auth): Simple token-based authentication.
- [Sanic-HTTPAuth](https://github.com/MihaiBalint/Sanic-HTTPAuth): Fork of Flask-HTTPAuth, provides Basic, Digest and Token HTTP authentication for Sanic routes
- [sanic-security](https://github.com/sunset-developer/sanic-security): A powerful, simple, and async security library for Sanic. 
- [SanicApiKey](https://github.com/Quiec/sanicapikey): Simple api key based authentication.
- [Sanic-Auth](https://github.com/pyx/sanic-auth): A tiny extension provide a decorator @auth.login_required, without Authentication algorithm & Session manage (sanic-session can work togather).
- [Sanic-Beskar](https://github.com/pahrohfit/sanic-beskar): Strong, Simple, and Precise security for Sanic APIs.


### Development
- [Pytest-Sanic](https://github.com/yunstanford/pytest-sanic): A pytest plugin for Sanic. It helps you to test your code asynchronously.
- [Sanic-OpenAPI](https://github.com/sanic-org/sanic-openapi): OpenAPI support, plus a Swagger UI.
- [Sanic-Devtools](https://github.com/yunstanford/sanic-devtools): Dev tools for Sanic.

### Frontend
- [sanja](https://github.com/tomaszdrozdz/sanja): This module aims to make bringing Jinja templates to Sanic easy.  
- [Jinja2-sanic](https://github.com/yunstanford/jinja2-sanic): a jinja2 template renderer for Sanic.
- [Sanic-Babel](https://github.com/lixxu/sanic-babel): Adds i18n/l10n support to Sanic applications with the help of the `Babel` library
- [Sanic-CORS](https://github.com/ashleysommer/sanic-cors): A port of flask-cors.
- [Sanic-Jinja2](https://github.com/lixxu/sanic-jinja2): Support for Jinja2 template.
- [Sanic-Sass](https://github.com/Vepnar/Sanic-Sass): Compile Sass & SCSS to CSS for Sanic.

### Monitoring
- [Sanic-Prometheus](https://github.com/dkruchinin/sanic-prometheus): Prometheus metrics for Sanic
- [Prometheus-Sanic](https://github.com/skar404/prometheus-sanic): Fork: [dkruchinin/sanic-prometheus](https://github.com/dkruchinin/sanic-prometheus)
- [Sanic-Rollbar](https://github.com/saabeilin/sanic-rollbar): Rollbar (exception reporting) integration for Sanic
- [Sanic-Sentry](https://github.com/serathius/sanic-sentry): Sentry integration for Sanic.
- [Sanic-Statsd](https://github.com/saabeilin/sanic-statsd): StatsD (currently only DataDog; WIP) metrics collection for Sanic

### ORM
- [GINO](https://github.com/fantix/gino): A lightweight asynchronous ORM based on SQLAlchemy core, with asyncpg dialect and Sanic extension.
- [Tortoise ORM](https://github.com/tortoise/tortoise-orm):  an easy-to-use asyncio orm like Django
- [Sanic-Motor](https://github.com/lixxu/sanic-motor): Simple motor wrapper.
- [Sanic-mongodb-extension](https://github.com/Relrin/sanic-mongodb-extension): Extension for MongoDB with μMongo ODM support for Sanic framework
- [Mayim](https://ahopkins.github.io/mayim/):  The *NOT* ORM Python hydrator

### Requests and Responses
- [Webargs-Sanic](https://github.com/EndurantDevs/webargs-sanic): Sanic integration with [Webargs](https://github.com/marshmallow-code/webargs). Parse & validate request arguments: headers, arguments, cookies, files, json, etc.
- [Python-Sanicargs](https://github.com/trustpilot/python-sanicargs): Parse query args in Sanic using type annotations and a decorator.
- [Sanic Brogz](https://github.com/michaelchisari/sanic_brogz): Allows you to easily gzip Sanic responses. A port of Flask-Compress.
- [Sanic Gzip](https://github.com/koug44/sanic-gzip): Add compression to your Sanic endpoints with a decorator
- [Sanic-Limiter](https://github.com/bohea/sanic-limiter): Rate limiting for sanic.
- [Sanic-UserAgent](https://github.com/lixxu/sanic-useragent): Add `user_agent` to request
- [Sanic-SSLify](https://github.com/dzqdzq/sanic_sslify): Forces SSL on your Sanic app. A port of Flask-SSLify.
- [TuSanic](https://github.com/avi-av/TuSanic): TuSanic is a [tus.io](https://tus.io) (simple _resumable uploads_) server-side implementation for sanic

### Caching
- [Sanic-redis-extension](https://github.com/Relrin/sanic-redis-extension): Redis (via aioredis) support for Sanic framework 

### Tracing
- [Sanic-OpenTracing](https://github.com/itechub/sanic-opentracing): Distributed tracing with [OpenTracing](https://opentracing.io/).

### Queues
- [Sanic-amqp-extension](https://github.com/Relrin/sanic-amqp-extension): AMQP support for Sanic framework

### Scaffolding
- [Cookiecutter-Sanic](https://github.com/harshanarayana/cookiecutter-sanic): Get your sanic application up and running in a matter of second in a well defined project structure. Batteries included for deployment, unit testing, automated release management and changelog generation.

### Session
- [Sanic Sessions](https://github.com/xen/sanic_session): Session support for humans. Works with different backends Redis, Mongodb, memcache or an in memory store.


### Utils
- [Python-Paginate](https://github.com/lixxu/python-paginate): Simple pagination support.
- [Sanic-Dispatch](https://github.com/ashleysommer/sanic-dispatcher): A dispatcher inspired by `DispatcherMiddleware` in werkzeug. Can act as a Sanic-to-WSGI adapter.
- [Sanic-EnvConfig](https://github.com/jamesstidard/sanic-envconfig): Pull environment variables into your sanic config.
- [sanic-sse](https://github.com/inn0kenty/sanic_sse): [Server-Sent Events](https://en.wikipedia.org/wiki/Server-sent_events) implementation for Sanic.
- [Sanic-CamelCase-Middleware](https://nf1s.github.io/sanic-camelcase-middleware/): Middleware for camelizing request and response bodies for sanic. 
- [Sanic-Pydantic](https://nf1s.github.io/sanic-pydantic/): A library for parsing and validating http requests for sanic web-framework using pydantic library.
- [sanic-dantic](https://github.com/miss85246/sanic-dantic): a sanic request parameter check plugin based on pydantic. support FBV and CBV
- [sanic-fire](https://github.com/tim2anna/sanic-fire): An extension for Sanic that adds support for writing external commands to your application.

## Resources

### Examples
- [SanicCRUD-vue](https://github.com/boylegu/SanicCRUD-vue): A example demo base Sanic with vueJS + webpack
- [Sanic-Nginx-Docker-Example](https://github.com/itielshwartz/sanic-nginx-docker-example): Simple and easy to use example of Sanic behined nginx using docker-compose.
- [Websocket PubSub Feed](https://gist.github.com/ahopkins/9816b39aedb2d409ef8d1b85f62e8bec): A starting point for building a websocket-based pubsub feed with Redis
- [Open Matchmaking Auth/Auth microservice](https://github.com/OpenMatchmaking/microservice-auth): Authentication / Authorization microservice for Open Matchmaking platform
- [Open Matchmaking Game servers pool microservice](https://github.com/OpenMatchmaking/microservice-game-servers-pool): Microservice for handling game servers pool
- [Open Matchmaking Player statistics microservice](https://github.com/OpenMatchmaking/microservice-player-statistics): Storage for player statistics
- [Sanic + Motor](https://github.com/humbss/sanic-motor-example): A starting point for building Sanic application integrated with Motor Mongo DB

### Tutorials 
- [Getting started with Sanic](https://www.twilio.com/blog/2016/12/getting-started-with-sanic-the-asynchronous-uvloop-based-web-framework-for-python-3-5.html)
- [Super Fast Voice Broadcast with Asynchronous Python and Sanic](https://www.nexmo.com/blog/2017/10/05/fast-voice-broadcast-python-dr/)
- [Deploying an asynchronous Python microservice with Sanic and Zeit Now](https://simonwillison.net/2017/Oct/14/async-python-sanic-now/)
- [Part I — Getting started with the Sanic web framework: initial setup and https](https://medium.com/@michealjroberts/getting-started-with-the-sanic-web-framework-initial-setup-and-https-730a1eb7c8e3)
- [How to make your code fast and asynchronous with Python and Sanic](https://medium.com/free-code-camp/goin-fast-and-asynchronous-with-python-and-sanic-387d722f3668)

### Books
- [Python Web Development with Sanic](https://sanicbook.com/): An in-depth guide for Python web developers to improve the speed and scalability of web applications, by Adam Hopkins

### Videos and Podcasts
- [Dougal Matthews - Async Web Apps with Sanic](https://www.youtube.com/watch?v=wb0lk4e9DEg&t=1s) - EuroPython 2017
- [Chris Hawkes - Python Sanic Tutorial](https://www.youtube.com/watch?v=WiGsWfwh0yY&t=3s)
- [Adam Hopkins, TalkPython - Episode #188: Async for the Pythonic web with Sanic](https://talkpython.fm/episodes/show/188/async-for-the-pythonic-web-with-sanic)
- [Adam Hopkins, EuroPython 2020 - Overcoming access control in web APIs](https://www.youtube.com/watch?v=Uqgoj43ky6A)
- [Adam Hopkins, PyConIL 2021 - Liberate your API: Building a task manager inside Sanic](https://www.youtube.com/watch?v=hGAwyg8_W3M)
- [DevGuyAhnaf, Full Featured Discord.py Bot Dashboard - Part 1: Making the Bot](https://www.youtube.com/watch?v=56Zw8-eaNq8) - 4 Parts on YouTube

### Built with Sanic

The following is a list of Sanic in production use.

* [chrome-prerender](https://github.com/bosondata/chrome-prerender)
* [Sanic-MDL-Blog](https://github.com/stopspazzing/Sanic-MDL-Blog)
* [aioquiz - workshop registration and execution](https://github.com/pdyba/aioquiz)
* [ethereumd-proxy](https://github.com/DeV1doR/ethereumd-proxy)
* [json-head](https://json-head.now.sh/): explained in [Deploying an asynchronous Python microservice with Sanic and Zeit Now](https://simonwillison.net/2017/Oct/14/async-python-sanic-now/)
* [datasette](https://github.com/simonw/datasette) - a tool for providing instant JSON API for your SQLite databases. [More information here](https://simonwillison.net/2017/Nov/13/datasette/).
* [devmap - Learning mindmaps](https://github.com/sourcepirate/devmap)
* [NMT - Network Mapper Tool](https://github.com/gbnk0/nmt) - A tool for mapping networks
* [TuringNetwork](https://github.com/turingnetworkai/turingnetwork) - A NeuralNetwork Visualization tool built on/for PyTorch/ONNX
* [exchangeratesapi.io](https://github.com/madisvain/exchangeratesapi) - Exchange rates with currency conversion
* [swagger-py-codegen](https://github.com/guokr/swagger-py-codegen) - a Python web framework generator supports Sanic, Flask, Tornado, Falcon
* [Simple-image-classifier](https://github.com/gbnk0/simple-image-classifier) - A microservice for image classification, based on tensorflow
