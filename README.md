# TinyFlowerBeds
[![Build Status](https://travis-ci.org/alwayslivid/TinyFlowerBeds.svg?branch=master)](https://travis-ci.org/alwayslivid/TinyFlowerBeds)

"Tiny Flower Beds" is a bot that posts a tiny flower bed on Twitter every few hours.
It is licensed under the GPL license.

## Getting started

In order to use this bot, you'll need to have access to the Twitter API.

You can request access and get your credentials [here.](https://dev.twitter.com)

The bot will check for a file called `credentials.py`.

`credentials.py` should have the following format:

```
CONSUMER_KEY = '<CONSUMER KEY>'
CONSUMER_SECRET = '<CONSUMER SECRET>'
ACCESS_KEY = '<ACCESS KEY>'
ACCESS_SECRET = '<ACCESS SECRET>'
```


By default, this bot will prioritize environment variables over the `credentials.py` file.

If you believe that environment variables are more convenient for you, then you will need to register the following keys:
* CONSUMER_KEY
* CONSUMER_SECRET
* ACCESS_KEY
* ACCESS_SECRET
... and assign those keys to their respective values.

## Prerequisites

* Python 3.6.7 is recommended. (*not* 3.7+)
* [Your Twitter account's API credentials.](https://dev.twitter.com)

### Live Demo
A live demonstration of my bot can be viewed [here.](https://twitter.com/tinyflowerbeds)

Should you host your own variation of this bot, please include the link to my account in the biography of the account. The `config` dictionary can be freely adjusted to your needs.

## Authors

* **Panagiotis Vasilopoulos** - *Initial work.* - [AlwaysLivid](https://alwayslivid.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
