# Searchor-main-app
Searchor is an innovative web application designed to streamline the search experience for users across various domains. The platform integrates advanced search algorithms with a user-friendly interface to deliver highly relevant and personalized results.


# Project Title: Searchor

# Description:
Searchor is an innovative web application designed to streamline the search experience for users across various domains. The platform integrates advanced search algorithms with a user-friendly interface to deliver highly relevant and personalized results.

# Key Features:
Intelligent Search: Employing state-of-the-art algorithms to enhance search accuracy and speed.
Personalized Recommendations: Offering tailored suggestions based on user preferences and search history.

# Multi-Domain Search:
A unified platform that supports searches across diverse categories such as articles, images, videos, and more.

# User-Friendly Interface: 
A clean and intuitive design for a seamless and enjoyable user experience.

# Advanced Filters:
Empowering users with granular control over search results through customizable filters.

# Real-Time Updates:
Keeping users informed with live updates on trending topics and breaking news.

# Target Audience:
Searchor caters to a wide range of users, including students, professionals, researchers, and anyone seeking a more efficient and personalized search experience.

# Why Choose Searchor:

Unparalleled search accuracy and efficiency.
A user-centric approach with a focus on personalization.
Versatility in supporting searches across multiple content types.
Continuous improvement through regular updates and user feedback.

# Technology Stack:
Backend: [Specify backend technologies]
Frontend: [Specify frontend technologies]
Database: [Specify database technologies]


# Future Enhancements:
Future iterations of Searchor will include features like voice search, language support expansion, and integration with emerging technologies.

# Conclusion:
Searchor is not just a search engine; it's a personalized discovery platform, revolutionizing the way users find and engage with information. Join us in this exciting journey towards a smarter and more efficient search experience.



Searchor
========


<img align="left" src="http://estruyf-github.azurewebsites.net/api/VisitorHit?user=ArjunSharda&repo=Searchor&countColorcountColor&countColor=%237B1E7B"/>
<img align="right" src="https://img.shields.io/github/repo-size/ArjunSharda/Searchor?style=for-the-badge&logo=appveyor" alt="GitHub repo size"/>

<img align="right" alt="Json-Generator" src="https://socialify.git.ci/ArjunSharda/Searchor/image?description=1&font=Rokkitt&forks=1&issues=1&language=1&logo=https%3A%2F%2Fgithub.com%2FArjunSharda%2FSearchor%2Fblob%2Fmain%2Fext%2Fsearchor.png%3Fraw%3Dtrue&name=1&owner=1&pattern=Floating%20Cogs&pulls=1&stargazers=1&theme=Light" />

<p align="center">
<img src="https://forthebadge.com/images/badges/built-with-love.svg" alt=" forks"/>
</p>

![PyPI](https://img.shields.io/pypi/v/searchor?color=green&logo=python&logoColor=green)
[![Discord](https://img.shields.io/discord/1026470859868741662)](https://discord.gg/fPXNMW7swn)
<div style="text-align: center; display: grid; justify-content: center;"><img style="margin: auto; margin-bottom: 1rem; border-radius: 30%;" height="150" width="150" src="https://raw.githubusercontent.com/ArjunSharda/Searchor/main/ext/searchor.png"/></div>


Installation
------------
**[Python 3.7+](https://www.python.org/downloads/) is required**
```bash
# MacOS / Linux (via Terminal)
python3 -m pip install -U searchor

# Windows (via CMD Prompt)
py -3 -m pip install -U searchor
```

Quick Start
-----------
```python
>>> from searchor import Engine
>>> Engine.Google.search("Hello, World!")
'https://www.google.com/search?q=Hello%2C%20World%21'
```

Searchor CLI Quick Start
---------
```shell
$ searchor Google "Hello World!" --copy
```
<br>
</br>

Take a look at more examples in the [examples](https://github.com/ArjunSharda/Searchor/tree/main/examples) folder!

*Note*:&nbsp; Engine names follow the **UpperCamelCase** convention.(eg: ChromeWebStore).

v2.3.2 Changes
--------------
- **[PATCHED]** Patched a bug with Amazon Web Services, Altassian, and Amazon being duplicates.

Migration
---------
Instead of different functions for each engine, Searchor `v2.2.0` uses a single function with an `Engine` enum. This makes it easier to use and maintain. If you're migrating from `v2.0.0`, compare the differences between the following snippets:
```python
# Searchor 2.0.0
from searchor import search, Engine
search("Hello, World!", Engine.Google)
```
```python
# Searchor v2.2.0
from searchor import Engine
Engine.Google.search("Hello, World!")
```

## Want to contribute?
Take a look at the [contributing guidelines](CONTRIBUTING.md)!

<hr>
<h6 align="center">© Arjun Sharda 2022 
<br>
All Rights Reserved</h6>

