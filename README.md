# Pushover

A very KISS [Pushover](https://pushover.net/) client for the command line

## Install

Get your user key & app token on https://pushover.net/

```sh
$ export PUSHOVER_APP_TOKEN=xxx
$ export PUSHOVER_USER_KEY=yyy
```
Better put it in your `.bashrc`or whatever you use

```sh
$ chmod +x pushover
```

Have it in your `$PATH`

## Usage

```sh
$ pushover "Hello, World !"
