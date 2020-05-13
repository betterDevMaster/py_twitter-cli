# Simple Twitter CLI Client

## Overview
It is a very simple Twitter CLI client made in Python that can perform the following two functions.
* Show my timeline
* Post a Tweet

## How to use
* Preparation 1
`` `
$ chmod + x twcli.py
`` `

* Preparation 2
`` `
$ touch ~ / .twclirc # Enter KEY and TOKEN
`` `
Described as follows. When posting a Tweet, make sure you have Write permission.
`` `
[twcli]
CONSUMER_KEY = XXXXXXXXXXXXXXXXXXXXX
CONSUMER_SECRET = XXXXXXXXXXXXXXXXXXXXX
ACCESS_TOKEN = XXXXXXXXXXXXXXXXXXXXXXXX
ACCESS_TOKEN_SECRET = XXXXXXXXXXXXXXXXXXXXX
`` `

* Display 10 timelines Show
`` `
./twcli.py tl -c 10
`` `

* Post a Tweet
`` `
./twcli.py tw -s "Hello from Twitter CLI Client"
`` `

## Motivation
* I wanted to try the Twitter API
* If it becomes a reference program for people who want to try Twitter API

## Dependencies
* [Python Fire](https://github.com/google/python-fire)
* [Requests-OAuthlib](https://github.com/requests/requests-oauthlib)

```
$ pip install requests requests_oauthlib fire
```