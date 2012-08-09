Node.js - npm-latest
====================

Quickly find the latest version of a package in `npm`.



Why?
----

I often forget which package version I need to put as a dependency in my packages. Running `npm info [package]` and then scrolling up scanning JSON became annoying.


Installation
------------

    npm install -g npm-latest



Example
------

    npm-latest express

output:

      express: 

        latest: 3.0.0rc2
        last updated: Fri Aug 03 2012 15:33:05 GMT-0500 (CDT)
        author: TJ Holowaychuk
        repo: git://github.com/visionmedia/express



License
-------

(MIT License)

Copyright 2012, JP Richardson <jprichardson@gmail.com>
