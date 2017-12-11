# firebase-log-tailer

[![npm version](https://badge.fury.io/js/firebase-log-tailer.svg)](https://badge.fury.io/js/firebase-log-tailer)

A Cloud Functions for Firebase log tailer.


## Install

```
$ npm -g install firebase-log-tailer
```

## Usage

```
$ firebase-log-tailer
2017-12-11T14:51:06.580809246Z D hoge: Function execution started
2017-12-11T14:51:06.593485208Z D hoge: Function execution took 93 ms, finished with status: 'ok'
....
```

## Options

```
$ npm-cli-sample -h

  Usage: npm-cli-sample [options]


  Options:

    --only <value>          only show logs of specified, comma-seperated functions (e.g. "funcA,funcB")
    -n, --lines <value>     specify number of log lines to fetch (default: 50)
    -i, --interval <value>  timeInterval (default: 20000)
    -h, --help              output usage information
```
