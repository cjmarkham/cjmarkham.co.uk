---
layout: project
title:  "Standards Checker"
url: ""
date:   2014-04-06 21:00:00
permalink: "projects/standards-checker"
tags: php regex mysql
---

Standards Checker is an application I made for our development team. With this application you can check to see if code within a file is to the standard you expect it to be.

The standards are specified within the source, as this is a company specific application. The checker will loop through every file from the root directory and display any lines that have not passed it's rules.

As a bonus, clicking said line will take you to a nicely formatted view of the file with the line in question highlighted. It will also point out who is likely to have made that edit thanks to pear style comment blocks. 