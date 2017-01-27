---
layout: essay
type: essay
title: Asking Questions the Smart Way
date: 2017-01-27
labels:
  - Software engineering
  - Learning
  - Effective communication
  - StackOverflow
---

## Introduction ##
Working with technology is difficult.  At some point, you will encounter an error, a bug, or a failure that will force you to do a little research.  Thankfully, there are a vast amount of websites, forums, and discussion boards that can assist with providing an answer.  Although the tech community is filled with knowledgable individuals who are willing to help, you can very easily find yourself without a paddle.  If you wish to receive a well-thought out response, you must be able to ask a "smart" question.  In Eric Raymond's article, [*How to ask questions the smart way*](http://www.catb.org/esr/faqs/smart-questions.html#volume), he provides guidelines for effectively communicating with the tech community, which starts even before you even engage with the community:

*Before asking a technical question by e-mail, or in a newsgroup, or on a website chat board, do the following: Try to find an answer by searching the archives of the forum or mailing list you plan to post to. Try to find an answer by searching the Web. Try to find an answer by reading the manual. Try to find an answer by reading a FAQ. Try to find an answer by inspection or experimentation. Try to find an answer by asking a skilled friend. If you’re a programmer, try to find an answer by reading the source code.*

Asking questions that could have been solved by doing a little reading, will yield little to no results, because you have shown that you are unwilling to learn.  Nobody wants to help someone who's looking for the easy way out.  By constructing a well formulated question, and providing examples, it makes it much easier for others to provide you with a constructive response that resolves the issue and helps you understand the material.

## Smart Questions ##
As an example, here is what is considered a "smart" question:

<img class="ui centered huge image" src="/images/smartquestion.png">

The question is simple, explicit, and the user describes his experiences with the issue.  He uses meaningful subject header tags to clearly describe his inquiry.  The user provides examples of the methods he's used and his results, which clearly demonstrates his attempt to find an answer through experimentation.  Additionally, the user is not asking a question for the sake of an answer.  He is making an attempt to truly understand when to properly use ```'=='``` and `'.equals()'`, and leaves room for good feedback and discussion.

As a result, the user was provided with a "smart" answer:

<img class="ui centered huge image" src="/images/smartanswer.png">

The person who responded understood that the user genuinely wished to understand the answer, rather than just receiving one.  The responder answers the user's questions with detailed explanations on the differences between `'=='` and `'.equals()'`.  They also provided commented code to help the user understand how and when to use the functions properly.  The rest of the thread is filled with similar answers from other users, with the same level of thoughtfulness and examples:

[http://stackoverflow.com/questions/513832/how-do-i-compare-strings-in-java](http://stackoverflow.com/questions/513832/how-do-i-compare-strings-in-java)

## Not Smart Questions ##
As an example, here is what is considered a "not smart" question:

<img class="ui centered huge image" src="/images/notsmartquestion.png">

Right off the bat, the user has already made it clear that they have posted a homework problem.  The user's post consists of the entire homework problem, and shows little to no effort in making an attempt to solve it.  The user's "request" for help is more of an "order" for someone else to start the assignment for them, regardless of the disclaimer.  No examples are provided of what the user has attempted, and vaguely describes how they are tackling the problem.  It shows a lack of effort and discipline to try and understand the concepts required for the assignment.  There is also no room for constructive feedback or criticism, as the user is only interested in others doing their work.

As a result, the user received a "not smart" answer:
<img class="ui centered huge image" src="/images/notsmartanswer.png">

The response is hollow and lacks any real substance other than the code necessary to start the assignment.  It may have been the right answer, but it provides no real benefit to the user other than fulfilling their request.  Although the code is provided, can the user really understand the concept of overloading by reading someone else's work?  In this case, the user should have been more explicit and stated what they do and don't understand about overloading to avoid having to make these requests in the future.  In addition, the response should have challenged the user to critically think about the assignment, to help the user fully grasp overloading.  The rest of the thread contains only one other answer, which vaguely responds to the user's question and provides a link to documentation:

[http://stackoverflow.com/questions/20365037/homework-and-overloading-in-java](http://stackoverflow.com/questions/20365037/homework-and-overloading-in-java)

## Lessons Learned ##
Following these guidelines is important for anyone in a tech related field, because as a member of the tech community, everyone is held to a certain level of discipline and effort.  Nobody wants to help someone who refuses to help themself.  It seems a little cut-throat, but it's a waste of everyone's time when the same questions have to be answered.  When interacting with the online open-source community, you need to effectively communicate in order to receive the results that you want.  Showing a genuine interest in your work, and being courteous to others is a powerful tool for attracting people who want to help you.
