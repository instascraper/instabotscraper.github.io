---
layout: page
title: Installation instructions on Windows
permalink: /docs/en/Installation_on_Windows/
---

**Important! Read the instructions from start to finish, and then act! Good luck!**

## Installing Python 3

1. Go to the Python [website](https://www.python.org/downloads/).
2. Choose the version that suits you (depends on the operating system).
3. Download.
4. Run the installer.
5. Follow the instructions that the installer offers you. Check "Add Python 3.x to Path" and click on Install Now (see the figure below). If you are an experienced user, select Customize installation.
![Install Python 3 and add to PATH]({{ site.url }}/docs/install_python_on_Windows.PNG "Install Python 3 and add to PATH")
## Downloading a project from GitHub

There are two options for downloading the project:

a) Click the link https://github.com/instagrambot/Instagram-scraper-with-autopost Click on "Clone or download", and then on "Download ZIP". Unpack it.
b) Installing the Git Client:
1. Go to the Git [site](https://git-scm.com/downloads).
2. Choose the version that suits you (depends on the operating system).
3. Download.
4. Run the installer.
5. Follow the instructions that the installer suggests (click on Next). You can configure the client yourself if you are an experienced user.
6. After installation, run the command line.
7. At the command prompt, type.

## Install Dblib
Download dlip ‘.wheel’ file as ur system requirnment (use link bellow)
download link : https://pypi.python.org/simple/dlib/

```
Open cmd navigate to dlib wheel file path and hit command
pip install dlib_file_name.wheel
```

## Then run

``` bash
git clone https://github.com/instagrambot/Instagram-scraper-with-autopost --recursive
```

```
cd Instagram-scraper-with-autopost
```

```
pip install -r requirements.txt
```

```
change yourusername to your instagram username in file example.py line 29: InstaUsername = "yourusername"
```

```
change instaprofiles.txt to the instagram profiles you wanna scrape
```

```
Run: python example.py -u yourusername
```

```
And press Enter.

***Congratulations! You downloaded the project!***

