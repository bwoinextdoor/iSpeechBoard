# Contributing to iSpeechBoard

Interested in contributing to iSpeechBoard? Thanks! There are plenty of ways you can help.

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue or assessing patches and features.

## Ways of contributing

- As a developer
- As a translator
- As a manual tester
- As an automation tester

## As a developer

### What you need to know

In order to contribute as a developer, you will need to have a basic understanding of [React](https://facebook.github.io/react/docs/hello-world.html) and probably [Redux](https://egghead.io/courses/getting-started-with-redux), you will also need to be familiar with [Material-UI](https://material-ui.com/).

### Submitting a Pull Request

Good pull requests, such as patches, improvements, and new features, are a fantastic help. They should remain focused in scope and avoid containing unrelated commits.

Please **ask first** if somebody else is already working on this or the core developers think your feature is in-scope for iSpeechBoard. Generally always have a related issue with discussions for whatever you are including.

### Setting Up a Local Copy

1. Clone the repo with `git clone https://github.com/bwoinextdoor/iSpeechBoard`

2. Run `yarn install` in the root `iSpeechBoard` folder.

Once it is done, you can modify any file locally and run `yarn start`, `yarn test` or `yarn run build`.

## As a translator

We currently support 40 languages, most of which were machine translated and require proofreading.
Help us make iSpeechBoard available in your country!

## As a manual tester

Our issue tracker is quite active, typically we got two-three bugs/week, then active tester participation is highly appreciated in order to clarify, reproduce, and track the bugs.
**We need help on writing a test plan!**
We have never written a test plan for iSpeechBoard and it feels really bad. We will appreciate people that is able to design and create a comprehensive test plan covering all of the features and functions of the applications that are available in the iSpeechBoard system.

## As an automation tester

If you are proficient with automation testing, we will be happy if you can help us!.
We have developed a little automation framework based on [Webdriver.io](https://webdriver.io/), that runs using the cloud service provided by [Browserstack](https://www.browserstack.com/).
