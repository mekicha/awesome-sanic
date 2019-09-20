# Awesome Sanic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [Sanic](https://sanicframework.org/) resources and extensions  
> Sanic is an Async Python 3.5+ web server that's written to go fast

[Docs](https://sanic.readthedocs.io/) | [Source](https://github.com/huge-success/sanic) | [Forums](https://community.sanicframework.org/)


## Contents
- [Extensions](#extensions)
    - [API](#api)
    - [Authentication](#authentication)
    - [Development](#development)
    - [Frontend](#frontend)
    - [Monitoring](#monitoring)
    - [ORM](#orm)    
    - [Requests and Responses](#requests-and-responses)
    - [Scaffolding](#scaffolding)    
    - [Session](#session)
    - [Utils](#utils)
- [Resources](#resources)
    - [Examples](#examples)
    - [Podcasts](#podcasts)
    - [Videos and Podcasts](#videos-and-podcasts)
    - [Built with Sanic](#built-with-sanic)


## Extensions

### API
- [Sanic CRUD](https://github.com/Typhon66/sanic_crud): CRUD REST API generation with peewee models.
- [Sanic-GraphQL](https://github.com/graphql-python/sanic-graphql): GraphQL integration with Sanic
- [Sanic-RestPlus](https://github.com/ashleysommer/sanic-restplus): A port of Flask-RestPlus for Sanic. Full-featured REST API with SwaggerUI generation.
- [Sanic-Transmute](https://github.com/yunstanford/sanic-transmute): A Sanic extension that generates APIs from python function and classes, and also generates Swagger UI/documentation automatically.

### Authentication
- [Sanic-JWT](https://github.com/ahopkins/sanic-jwt): Authentication extension for JSON Web Tokens (JWT).
- [Sanic-JWT-Extended](https://github.com/NovemberOscar/Sanic-JWT-Extended): Port of flask-jwt-extended, provides access/refresh token with fresh, easy custom claim insertion, and role-based access control
- [Sanic-OAuth](https://gitlab.com/SirEdvin/sanic-oauth): OAuth Library with many provider and OAuth1/OAuth2 support.
- [Sanic-Token-Auth](https://github.com/saabeilin/sanic-token-auth): Simple token-based authentication.
- [Sanic-HTTPAuth](https://github.com/MihaiBalint/Sanic-HTTPAuth): Fork of Flask-HTTPAuth, provides Basic, Digest and Token HTTP authentication for Sanic routes

### Development
- [Pytest-Sanic](https://github.com/yunstanford/pytest-sanic): A pytest plugin for Sanic. It helps you to test your code asynchronously.
- [Sanic-OpenAPI](https://github.com/channelcat/sanic-openapi): OpenAPI support, plus a Swagger UI.
- [Sanic-Devtools](https://github.com/yunstanford/sanic-devtools): Dev tools for Sanic.

### Frontend
- [Jinja2-sanic](https://github.com/yunstanford/jinja2-sanic): a jinja2 template renderer for Sanic.
- [Sanic-Babel](https://github.com/lixxu/sanic-babel): Adds i18n/l10n support to Sanic applications with the help of the `Babel` library
- [Sanic-CORS](https://github.com/ashleysommer/sanic-cors): A port of flask-cors.
- [Sanic-Jinja2](https://github.com/lixxu/sanic-jinja2): Support for Jinja2 template.

### Monitoring
- [Sanic-Prometheus](https://github.com/dkruchinin/sanic-prometheus): Prometheus metrics for Sanic
- [Sanic-Rollbar](https://github.com/saabeilin/sanic-rollbar): Rollbar (exception reporting) integration for Sanic
- [Sanic-Sentry](https://github.com/serathius/sanic-sentry): Sentry integration for Sanic.
- [Sanic-Statsd](https://github.com/saabeilin/sanic-statsd): StatsD (currently only DataDog; WIP) metrics collection for Sanic

### ORM
- [GINO](https://github.com/fantix/gino): A lightweight asynchronous ORM based on SQLAlchemy core, with asyncpg dialect and Sanic extension.
- [Sanic-Motor](https://github.com/lixxu/sanic-motor): Simple motor wrapper.

### Requests and Responses
- [Python-Sanicargs](https://github.com/trustpilot/python-sanicargs): Parse query args in Sanic using type annotations and a decorator.
- [Sanic Brogz](https://github.com/michaelchisari/sanic_brogz): Allows you to easily gzip Sanic responses. A port of Flask-Compress.
- [Sanic Gzip](https://github.com/koug44/sanic-gzip): Add compression to your Sanic endpoints with a decorator
- [Sanic-Limiter](https://github.com/bohea/sanic-limiter): Rate limiting for sanic.
- [Sanic-UserAgent](https://github.com/lixxu/sanic-useragent): Add `user_agent` to request

### Scaffolding
- [Cookiecutter-Sanic](https://github.com/harshanarayana/cookiecutter-sanic): Get your sanic application up and running in a matter of second in a well defined project structure. Batteries included for deployment, unit testing, automated release management and changelog generation.

### Session
- [Sanic Sessions](https://github.com/xen/sanic_session): Session support for humans. Works with different backends Redis, Mongodb, memcache or an in memory store.


### Utils
- [Python-Paginate](https://github.com/lixxu/python-paginate): Simple pagination support.
- [Sanic-Dispatch](https://github.com/ashleysommer/sanic-dispatcher): A dispatcher inspired by `DispatcherMiddleware` in werkzeug. Can act as a Sanic-to-WSGI adapter.
- [Sanic-EnvConfig](https://github.com/jamesstidard/sanic-envconfig): Pull environment variables into your sanic config.


## Resources

### Examples
- [SanicCRUD-vue](https://github.com/boylegu/SanicCRUD-vue): A example demo base Sanic with vueJS + webpack
- [Sanic-Nginx-Docker-Example](https://github.com/itielshwartz/sanic-nginx-docker-example): Simple and easy to use example of Sanic behined nginx using docker-compose.
- [Websocket PubSub Feed](https://gist.github.com/ahopkins/9816b39aedb2d409ef8d1b85f62e8bec): A starting point for building a websocket-based pubsub feed with Redis

### Tutorials 
- [Getting started with Sanic](https://www.twilio.com/blog/2016/12/getting-started-with-sanic-the-asynchronous-uvloop-based-web-framework-for-python-3-5.html)
- [Super Fast Voice Broadcast with Asynchronous Python and Sanic](https://www.nexmo.com/blog/2017/10/05/fast-voice-broadcast-python-dr/)
- [Deploying an asynchronous Python microservice with Sanic and Zeit Now](https://simonwillison.net/2017/Oct/14/async-python-sanic-now/)
- [Part I — Getting started with the Sanic web framework: initial setup and https](https://medium.com/@michealjroberts/getting-started-with-the-sanic-web-framework-initial-setup-and-https-730a1eb7c8e3)

### Videos and Podcasts
- [Dougal Matthews - Async Web Apps with Sanic](https://www.youtube.com/watch?v=wb0lk4e9DEg&t=1s) - EuroPython 2017
- [Chris Hawkes - Python Sanic Tutorial](https://www.youtube.com/watch?v=WiGsWfwh0yY&t=3s)
- [TalkPython - Episode #188: Async for the Pythonic web with Sanic](https://talkpython.fm/episodes/show/188/async-for-the-pythonic-web-with-sanic)

### Built with Sanic
> Taken from [The wiki](https://github.com/channelcat/sanic/wiki/Projects)

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
