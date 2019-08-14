---
layout: main
img: scribe
img_link: https://en.wikipedia.org/wiki/Scribe#/media/File:Escribano.jpg
img_credit: Escribano by Jean Le Tavernier. Public Domain via Wikimedia Commons.
title: Schedule
active_tab: schedule
---

# Daily Homework

Beginning on the second day of class, each student in LING 402 is responsible for daily practice homework. The idea is for you to log in to the cl server, and then actively practice the command line tools you have learned.
 
* Each week (Sunday through Saturday) you are responsible for completing and checking in to Github each practice session.
* At a minimum you must perform and check in one practice session on 5 separate days each week. You may do more than one practice session per day, but only one per day will count towards the minimum of 5 sessions per week.
* In order to receive full credit for a practice session, you must be actively working at the command line for a minimum of 10 full minutes. When grading your sessions, we have the ability to play back your session and see what you were doing; if you spend a non-trivial amount of time doing nothing or doing very little, you will not receive full credit, and you may receive zero credit.
* Reading documentation, including reading man pages, is very important and is highly encouraged. However, the practice sessions are not the most appropriate time for doing so. It's OK to quickly check a man page during your practice session. However, if you spend a non-trivial amount of time just reading during your practice session, you will not receive full credit, and you may receive zero credit.
* Before you begin your practice session, you are required to write a short summary explaining what you plan to do in your practice session.
* After you finish your practice session, you are required to write a slightly longer summary explaining in more detail what you actually did in your practice session.
 
* In week 1 of the semester, you are responsible for completing at least 2 practice sessions. Beginning in week 2, and continuing through the last full week of the semester, you will be responsible for completing at least 5 practice sessions per week, where each week is reckoned as Sunday through Saturday. You are not responsible for completing daily homework during the week of Thanksgiving. During the final week of classes, we only meet for class once; as such, that week you will be responsible for completing at least 2 practice sessions.
 
To begin:
 
* Log in to https://github.com
* Go to https://github.com/20XX-Fall-UIUC-LING402 (replace 20XX with the current year), and look for a repository with your username and "daily" in the name
* Click the green button that says "Clone or Download"
* A small pop-up should appear.
* In the pop-up, click the small link in the corner that says "Use HTTPS"
* In the pop-up, select the URL and copy it
* Log in to the cl server: ssh yourNetID@cl.linguistics.illinois.edu
* At the command line on the cl server, clone the repository:
 
```
$ git clone https://github.com/20XX-Fall-UIUC-LING402/yourGithubID-daily.git
```

In the above, you will need to replace 20XX with the current year and use your actual Github userID rather than "yourGithubID"
 
Now, to actually perform a daily homework practice session, use cd to navigate into the new directory, and then run ./practice.sh. That script will do the following:
 
* Prompt you to enter a pre-session description of what you are about to practice.
* Prompt you to start the session
* Provide you with a command line where you can practice. When you are done practicing, you will need to type exit to end the session.
* Prompt you to enter a post-session description of what you just practiced.
* Prompt you to commit and push your work to github.
 
Doing the daily homework is an important component of this class. It will help reinforce the material you learn, and help make you more comfortable working at the command line. It also represents a non-trivial portion of your grade, so you are strongly advised to take it seriously. In the past, I have had students who otherwise were doing well in the class not achieve the grade they were working towards due to not regularly completing their daily homework.
