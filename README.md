# hapi-project

Website hosted on Heroku [here](https://hapi-appi.herokuapp.com/).

[![Build Status](https://travis-ci.org/a-la-node/hapi-project.svg?branch=master)](https://travis-ci.org/a-la-node/hapi-project)
[![codecov](https://codecov.io/gh/a-la-node/hapi-project/branch/master/graph/badge.svg)](https://codecov.io/gh/a-la-node/hapi-project)
[![Code Climate](https://codeclimate.com/github/a-la-node/hapi-project/badges/gpa.svg)](https://codeclimate.com/github/a-la-node/hapi-project)
[![Issue Count](https://codeclimate.com/github/a-la-node/hapi-project/badges/issue_count.svg)](https://codeclimate.com/github/a-la-node/hapi-project)

![homepage mockup](mockups/Home_page.png)
![results mockup](mockups/Results.png)

[Original mockup](https://github.com/a-la-node/hapi-project/blob/master/public/images/HapiAppMockup.png "Original Mockup")

[UX Prototype](https://github.com/a-la-node/hapi-project/blob/master/public/images/proto.gif "UX Prototype")

## What?
- Create a templated web app using hapi
- Utilise 2 APIs - random name generator and nomad - finding working and living space
- Strong test coverage

## User Story

### General User Story
As... someone who wants to start a new life
I want to... be able to create a new identity
and get suggestions on where to start my new life.

### Broken-down User Stories

As an...  ex-convict
I want to... be able to create a new name
so that... I can recreate myself.

As a... witness (in a court trial)
I want to... find somewhere to stay
so that... I have a roof over my head whilst escape the criminals trying to hunt me down.

As a... bad spouse who has been thrown out
I want to... find somewhere to work
so that... I can earn some cash whilst I move around and re-piece my relationship.

As a... spy
I want to... be able to create a new identity (job/ phone no etc)
so that... I can trick the people I encounter and obtain crucial insider information.

Different users get different results based on their appetite for risk and budget. Spies are looking for somewhere cheap but happy to be risky, business executives are looking for something safer but happier to spend more money.

## How?
- TDD using server.inject for testing
- Host the project on heroku
- Try to use basic ES6 syntax
- Pair programming


## Stretch Goals
- Tailor users' results to their custom preferences
- Display users' results in a more visually organised/ appealing way (hide irrelevant options)

## Setup
- To install npm dependencies:
```
npm install
```
- To run the server:
```
npm run devStart
```
- To run tests:
```
npm test
```
- To check code coverage run:
```
npm run coverage
```
