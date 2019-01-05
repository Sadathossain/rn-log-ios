# RN-LOG-IOS

This repository contains a nodejs cli package to stream the ios simulator logs for react-native development environment.

## Why I have written this?

As the new xcode has moved all logs to console app, `react-native log-ios` command can not stream all the logs produced by simulator. Besides I wanted to produce clean development logs without all the cluttering advice messages, similar to `react-native log-android`

## Installation

For global installation

```sh
$ yarn global add rn-log-ios
# or
$ npm install -g rn-log-ios
```

For local installation

```sh
$ yarn add rn-log-ios
# or
$ npm install -g --save rn-log-ios
```

## Usage

```sh
$ rn-log-ios <YourAppName>
```

