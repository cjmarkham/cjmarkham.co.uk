---
layout: project
title:  "Mongo Admin"
url: ""
date:   2014-04-06 21:00:00
permalink: "projects/mongo-admin"
tags: mongodb php
---

Madmin is a a project I had been thinking about for a while.

I wanted to make a user interface for MongoDB that would help users of Sql databases. Madmin therefore comes with a tabular view of collections and their documents as well as a raw JSON view.

Users can enter their server, port and auth credentials. From there they can create collections, drop them, drop and create database and edit collections. It also comes with Schema. When a collection is created users can select from dates, strings and integers. I will eventually be creating a mongo wrapper which also uses the Schema.