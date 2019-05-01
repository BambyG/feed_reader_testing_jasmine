# Project Overview

For this project, I am given a web-based application that reads RSS feeds that needs several test suits to be written using [Jasmine](http://jasmine.github.io/). 


# The tests suits

Here are the following test written: 

- a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined _and_ that the URL is not empty

- a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
 
- a test that ensures the menu element is hidden by default

- a test that ensures the menu changes visibility when the menu icon is clicked. 

- a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container

- a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes

# Technologies

* HMTL
* CSS
* JAVASCRIPT

# Launch

 The project does not have minimum hardware requirements.
 Just view the HTML Page in Your Browser.


# Contributing 

This project was written by Bamby Gassama inspired by Udacity Nanodegree 4th project assignment. 

# Licence

The MIT License (MIT)

Copyright (c) 2019 Bamby Gassama

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
