---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

Developing a web application can be quit frustrating when you are unfamiliar with the tools at your disposal.  This happened to be the case with Meteor, during my development of the Digits application.  However, learning from these frustrations has better prepared me for the upcoming struggles and headaches that are soon to come when dealing with software engineering.

The problem that I encountered which frustrated me the most, occurred during the intial setup phase of the application.  After trying to invoking ```meteor --settings ../config/settings.development.json``` in Terminal, I found myself at a lost when the system was not running properly on localhost:3000.  Puzzled, I killed the process and deleted the folder hosting the app, and started from scratch.  However, on my second try, I encountered the same error.  After searching meticulously through Google for several minutes, I stumbled upon a post which suggested I try to update Meteor.  Surely enough, I found myself up and running again.
