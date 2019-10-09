---
layout: post
title: Developer Tools - What Should You Use? Here's our list
category: General
tags: [developer tools, general]
---
When you work as a developer or build knowledge on your way to becoming one you ought to stay focused. Choosing the right tools could help a lot, and by the right tools, I really mean the ones that do for you. Nowadays there is much choice, maybe even too much some would say, but in the end, it’s all a matter of preference. 

It's a bit confusing when you are just starting to make sense of the offers out there and I know it first-hand. For example, I kept changing text editors because none of the ones I tried looked or behaved exactly how I wanted. I eventually had to settle and chose the one I considered the best in the bunch. 

All this mumbo-jumbo about text editors (or other tools for that matter) might sound silly but it’s actually not. In my humble opinion, one should not waste a lot of time and energy on changing, reconfiguring and learning to use new tools because in the end, even if they come from different providers, they all do the same thing i.e. allow you to write, format and save text files (if we consider the example with the text editors). 

I always go with the principle that I can only recommend something if I tried it, or if I would buy/get it for myself. Thus, without further ado, here follows a list of what I currently use and like to work with.

### Editors/IDEs
Since we talked about text editors earlier, I’ll start there. At <Cub|e|vo>[https://cubevodata.com], we mainly write Python code so, the go-to utensil in our toolbox would be without a doubt JetBrains’ [PyCharm](< https://www.jetbrains.com/pycharm/>). The leaning curve is a bit steeper than, let’s say, SublimeText, but it contains everything you need (debugger, VCS integration, syntax highlighting, code completion and formatting, etc.), and, once you get the hang of it you just won’t want to use anything else. It’s a paid product but one can also download the Community version that is free. 
I also use [SublimeText](< https://www.sublimetext.com/>) as a secondary editor, mainly for ad-hoc script editing. It does not have the functionality of PyCharm, but you just have to love its simplicity. 

For data science or at least data-related projects, [Jupyter Lab](< https://github.com/jupyterlab/jupyterlab>) is a great choice because it allows you to execute code in chunks and view the output values or the errors that get generated for every step. 

### Programming language(s)
As far as programming languages go, the choice is endless. If you also want to do web development, you absolutely have to learn HTML, CSS, and JavaScript. You really don’t have much of a choice here. Other than those we mainly use Python and, not so often, R and Java, for other, more specific, tasks.

The choice to work with Python was a no-brainer for us because it’s relatively simple to get a grasp on, has a large community of contributors that is only growing every day, and it’s very versatile. This becomes obvious when you consider that it’s the main programming language used in data science, also used for web development, testing, automation, etc. It does a bit of everything and it seems to be doing them rather well. 

Last but not least, Python has a very large number of extensions, for everything you can think of. There the SciPy package for scientific numerical calculations, pandas for data manipulation, matplotlib for visualization, selenium integration for test automation, Django/Flask for web development, etc. Give it a few years and someone will surely develop packages that cook your food or do your laundry! 

The Cub|e|vo stack includes the [Anaconda](< https://www.anaconda.com/distribution/#download-section>) distribution, from Continuum Analytics. Not only is it very stable and well maintained, but it also comes with a very large array of extensions and tools in the installation kit. Thus, with one installation, you also get Jupyter, SciPy, pandas, matplotlib, SciKit-Learn, TensorFlow, VS Code, Spyder (an IDE developed specifically for data science), Orange (for data mining) and other goodies. It even includes Flask, so you should be all set up to embark onto your development adventure.   

### Database
In the database department, you should definitely try [PostgreSQL](< https://www.postgresql.org/>) and [SQLite](< https://www.sqlite.org/index.html>). The first one, we use for large projects, as it’s a full-fledged database system, and the second for smaller ones. [DBeaver](<https://dbeaver.io/>) is a great DB exploration and manipulation tool and I warmly recommend it. 

### Data preparation/preprocessing
For initial data exploration and preparation (preprocessing, duplicate removal, correction of some inconsistencies), MS Excel is still the preferred tool. Nevertheless, the most added value I find it is given by [OpenRefine](< http://openrefine.org/>) which does a lot of the heavy lifting for you in the cleansing process. It’s a project supported by Google News, and this adds to its street cred. 

### Communication
Writing code is very important but so is communication. One has to remain in contact with clients, colleagues, mentors, etc. Even more so if the work is done remotely. [Slack](< https://slack.com/>) is a great tool for teams. We’ve used it for projects, for coordinating ever-changing teams and it was quite useful.

If you also need to hold voice or video calls, eventually with screen-sharing and chat, [zoom](< https://zoom.us/>) is the way to go. In the free tier, you have a 40-minute time limit per session, but, given that the trend these days is to decrease the duration of meetings, it is quite ok. 

### More general aspects
The repositories for our current projects are all on [GitHub](< https://github.com/>). Should you not like it, try [GitLab](< https://about.gitlab.com/>) or [BitBucket](< https://bitbucket.org/>), they are both great.

The other documents we mainly store on [Google Drive](< https://www.google.com/drive/>), and any notes, thoughts, plans and to do lists in [Keep](< https://keep.google.com/>) or [Trello](< https://trello.com/>), depending on their nature. For administrative purposes, we also make use of the other Google tools like Sheets and [Gmail](< https://mail.google.com>). 

As far as OS goes, we work and test on multiple machines, with Windows 10, MacOS, Ubuntu (on [WSL](< https://docs.microsoft.com/en-us/windows/wsl/install-win10>)) and also on Google Cloud and AWS instances, so, having everything online, certainly helps. 

The tests are done in all major browsers ([Chrome](< https://www.google.com/chrome/>), [Firefox](< https://www.mozilla.org/ro/firefox/new/>) and [Opera](< https://www.opera.com/>); Safari on Mac), but also on Internet Explorer, Edge, Vivaldi and Brave. The main one though would be Chrome because the [DevTools](< https://developers.google.com/web/tools/chrome-devtools/>) are quite intuitive and easy to use. 

Before closing, I have to mention, if only in passing, [Workbench](< https://workbench.developerforce.com/>) which you will certainly want to use in SalesForce related projects, especially those where you need to work with data and study the composition of the various objects.  

### Closing notes
I would like to point out that, other than Excel, which is obviously a commercial program, all the other stuff mentioned in this article is free, or they have a free tier. 

We’d really like to know what you are using and why, so I invite you to leave a comment and let us know. 

Until next time, stay curious!
