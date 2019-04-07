---
layout: page
title: Installation on Unix
permalink: /docs/en/Installation_on_Unix/
---

# How to install and run the script on Unix? (Linux, macOS)
* Open terminal and run.

```
git clone https://github.com/instagrambot/Instagram-scraper-with-autopost --recursive
```

```
cd Instagram-scraper-with-autopost
```

```
sudo pip install -r requirements.txt
```



* change yourusername to your instagram username in file example.py line 29: InstaUsername = "yourusername"


* change instaprofiles.txt to the instagram profiles you wanna scrape


```
Run: python example.py -u yourusername
```


```
And press Enter.
 
```


## Errors

* If you have `pip: command not found` error, try:
```
sudo easy_install pip
```

