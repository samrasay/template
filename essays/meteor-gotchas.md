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

The problem that I encountered which frustrated me the most, occurred during the intial setup phase of the application.  After trying to invoking ```meteor --settings ../config/settings.development.json``` in Terminal, I found myself at a lost when the system was not running properly on localhost:3000.  Puzzled, I killed the process and deleted the folder hosting the app, and started from scratch.  However, on my second try, I encountered the same error.  After searching meticulously through Google for half an hour on StackOverflow, I stumbled upon a post which suggested I try to update Meteor.  Baffled by the simplicity of the answer, I tried several other suggestions before actually updating.  After many failures with those suggestions, I updated Meteor and surely enough I found myself up and running again.

Another problem that I encountered while developing the Digits application, was creating the "Edit Contact" page and displaying it properly within my browser.  As I was working through the development of the "Edit Contact" page, I had intended for the page to redirect to the url ```/edit-contact/:id```.  However, upon entering the url into my browser, the page would not load.  I spent several minutes trying to restart and troubleshoot Meteor, thinking there was an error with the server.  After restarting Meteor brought no success, I deduced that the problem lied within the code in the router.  It turns out I had only specified the router to direct to the url ```/edit-contact/``` !

  
