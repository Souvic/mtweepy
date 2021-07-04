# Makes twitter scrapping with multiple twitters apps easy again!
[![License: MIT](https://img.shields.io/github/license/Souvic/mtweepy)](https://opensource.org/licenses/MIT)
[![stars](https://img.shields.io/github/stars/Souvic/mtweepy)]()
[![Github All Releases](https://img.shields.io/github/downloads/huggingface/transformers/total.svg)]()
[![PyPI](https://img.shields.io/pypi/v/mtweepy)](https://pypi.org/project/mtweepy/)
[![python](https://img.shields.io/github/languages/top/Souvic/mtweepy)]()

[![Build Status](https://scrutinizer-ci.com/g/Souvic/mtweepy/badges/build.png?b=main)](https://scrutinizer-ci.com/g/Souvic/mtweepy/build-status/main)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/Souvic/mtweepy/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/Souvic/mtweepy/?branch=main)
[![Release date](https://img.shields.io/github/release-date/Souvic/mtweepy)]()
[![Latest Stable Version](https://img.shields.io/github/v/release/Souvic/mtweepy)]()

[![tweet](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FSouvic%2Fmtweepy)]()

### Support me


[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/Souvic)


Some appreciatory description
- [x] Lightweight
- [x] Easiest to use 

## Install from PyPi
```
pip3 install mtweepy
```

## Or Install from main branch
```
pip3 install git+https://github.com/Souvic/mtweepy.git
```

# Example usage
There are three functions in the repo: get_followers, get_timelines, get_users.
All the functions use all the auth tokens optimally for fastest scraping.
Apart from auths all the other inputs are self explantory.
As auths, a list of tweepy bearer tokens are expected if you want to use oauth2 limits for twitter api.
As auths, a list of \[client\_id,client_secret,user\_id, user\_token\] are expected if you want to use oauth2 limits for twitter api.
use_userid parameter is by default _False_. If it is passed as _True_ in get_followers, 
An example usage is provided here.
```
list_followers= get_followers("INCIndia", max_num=500)#gets list of followers appended in chunk of 5000, if max_num<5000, will get last 5000 followers.


```

You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

