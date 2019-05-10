---
layout: post
title: Developer Tools - What Should You Use? Here's my list
category: General
tags: [developer tools, general]
---
When you work as a developer or build knowledge on your way to becoming one you ought to stay focused. Choosing the right tools could help a lot, and by the right tools, I really mean the ones that do for you. Nowadays there is much choice, maybe even too much some would say, but in the end, it’s all a matter of preference. 

It's a bit confusing when you are just starting to make sense of the offers ot there and I know it first-hand. For example, I kept changing text editors because none of the ones I tried looked or behaved exactly how I wanted. I eventually had to settle and chose the one I considered the best in the bunch. 

All this mumbo-jumbo about text editors (or other tools for that matter) might sound silly but it’s actually not. In my humble opinion, one should not waste a lot of time and energy on changing, reconfiguring and learning to use new tools because in the end, even if they come from different providers, they all do the same thing i.e. allow you to write, format and save text files (if we consider the example with the text editors). 

I always go with the principle that I can only recommend something if I tried it, or if I would buy/get it for myself. Thus, without further ado, here follows a list of what I currently use and like to work with.

### Editors/IDEs
Since we talked about text editors earlier, I’ll start there. The go-to utensil in my toolbox would be without a doubt Microsoft’s [Visual Studio Code](< https://code.visualstudio.com/>). It has a simple and easy to use interface, good git integration, access to the console directly from VS Code, listing of problems in your peroject and it’s very extensible. If you find it lacking in some department, you can be quite sure that there’s an extension that might solve your problem. Not too long ago, I read an article saying that it had a high increase in popularity lately. Yes, it’s that good, and it’s also free. 

I also use [SublimeText](< https://www.sublimetext.com/>) as a secondary editor, mainly for ad-hoc script editing. It does not have the functionality of VS Code (at least not out-of-the-box), but I love its simplicity. 

For data science or at least data-related projects, I use [Jupyter Lab](< https://github.com/jupyterlab/jupyterlab>), and find it to be great because it allows you to execute code in chuncks the results or the errors that get generated with every step. 

I tried my hand with [PyCharm Community](< https://www.jetbrains.com/pycharm/download/#section=windows>) and [Visual Studio 2019 Community](< https://visualstudio.microsoft.com/downloads/>) but, at least for now, I'm content with what I already use and don't feel like switching.  

### Programming language(s)
As far as programming languages go, the choice is endless. If you also want to do web development you absolutely have to learn HTML, CSS, and JavaScript. You really don’t have much of a choice here. Other than those I mainly use Python and, not so often, R and VBA, for other, more specific, tasks.

I chose to work with Python because it’s relatively simple to get a grasp on it, has a large community of contributors that is only growing every day, and it’s very versatile. Its versatility is obvious when you consider that it’s the main programming language used in data science, also used for web development, testing, automation, etc. It basically does a bit of everything and it seems to be doing them rather well. 
Last but not least, Python has a very large database of extensions for everything you can think of. There the SciPy package for scientific numerical calculations, pandas for data manipulation, matplotlib for visualization, selenium integration for automation, Django/Flask for web development, etc. Give it a few years and someone will surely develop packages that cook your food or wash your laundry! 

But, although it’s very good at a lot of things, the relationship with Python is not always a bed of roses. In some cases it’s slow, even painfully slow I’d say, and it also does not do multi-core or multi-thread processing. The good news is that there are packages even for these cases like Cyton (for writing blazing fast extensions in C) and some libraries that enable multiprocessing. 

I use and recommend the [Anaconda](< https://www.anaconda.com/distribution/#download-section>) distribution, from Continuum Analytics. Not only is it very stable and well maintained, but it also comes with a very large array of extensions and tools in the installation kit. Thus, with one installation, you also get Jupyter, SciPy, pandas, matplotlib, SciKit-Learn, TensorFlow, VS Code, Spyder (an IDE developed specifically for data science), Orange (for data mining) and other goodies. As far as I remember it even comes with Flask preinstalled so you are ready to embark onto your development adventure.   

### Database
In the database department, you should definitely try [PostgreSQL](< https://www.postgresql.org/>) and [SQLite](< https://www.sqlite.org/index.html>). The first one, I use for more serious projects and the second for smaller ones. [DBeaver](<https://dbeaver.io/>) is a great DB exploration and manipulation tool and I warmly recommend it. 

### Data preparation/preprocessing
For initial data exploration and preparation (preprocessing, duplicate removal, correction of some inconsistencies), I use MS Excel, which is still a great tool these days. But the most added value I find it is given by [OpenRefine](< http://openrefine.org/>) which does a lot of the heavy lifting for you in the cleansing process. It’s a project supported by Google News, which should carry some weight. 

### Communication
Writing code is very important but so is communication. One has to remain in contact with clients, colleagues, mentors, etc. Even more so if the work is done remotely. [Slack](< https://slack.com/>) is a great tool for teams. I’ve used it for a project, for coordinating an ever-changing team and it was quite useful.

If you also need to hold calls or video calls, eventually with screen-sharing and chat, [zoom](< https://zoom.us/>) is the way to go. In the free tier, you have a 40-minute time limit per session, but, given that the trend these days is to decrease the duration of meetings, I’d say it’s quite ok. 

For less critical stuff, I use [WhatsApp](< https://www.whatsapp.com/>). Yes, it's depending on your phone to work but it also runs on computers in web browsers, or in the dedicated app, it’s totally free, you can send various types of files and it has an archive storing all that’s been transmitted. And as a bonus, the conversations are also encrypted. 

### More general aspects
To describe a bit my personal setup, I tend to have all my work stored in the cloud. The repositories for the projects are on [GitHub](< https://github.com/>), which I chose simply because I already had an account created some time ago and it was comfortable. Should you not like it, try [GitLab](< https://about.gitlab.com/>) or [BitBucket](< https://bitbucket.org/>), I hear they are both great.

The other documents I mainly store on [Google Drive](< https://www.google.com/drive/>), and any notes, thoughts, plans and to do lists in [Keep](< https://keep.google.com/>) or [Trello](< https://trello.com/>), depending on their nature. I also make use of the other Google tools like Sheets and [Gmail](< https://mail.google.com>). 

As far as OS goes, I work on multiple machines, on Windows 10, Ubuntu (on [WSL](< https://docs.microsoft.com/en-us/windows/wsl/install-win10>)) and MacOS X Mojave so having everything online certainly helps. [Git](< https://git-scm.com/>) is also a precious resource here, helping me to keep my work in order. 

I installed all major browsers ([Chrome](< https://www.google.com/chrome/>), [Firefox](< https://www.mozilla.org/ro/firefox/new/>) and [Opera](< https://www.opera.com/>); Safari on Mac). The main one though would be Chrome (yes, I have an inclination towards tools made in Google) as I’m accustomed to the [Chrome DevTools](< https://developers.google.com/web/tools/chrome-devtools/>). 

Before closing, I have to mention in passing [Workbench](< https://workbench.developerforce.com/>) which you will certainly want to use in SalesForce related projects, especially those where you need to work with data and study the composition of the various objects, and [Grammarly](< https://app.grammarly.com/>) for checking spelling or grammatical errors in your articles, emails, etc.  

### Closing notes
I would like to point out that, other than Excel, which is obviously a commercial program, all the other stuff I mentioned in this article is free, or they have a free tier. In fact, the only ones I pay for are the Google Drive’s 100GB option and an Office365 Business Premium subscription.

Another important aspect is that the links are present only to help the readers find the tools described more easily and not for commercial purposes. But then again, they wouldn’t represent paid publicity, would they… as my blog is still fresh out of the oven ?   

Lately, I have been exploring with a range of interesting stuff among which [WebAssembly](< https://webassembly.org/>), [Splunk](< https://www.splunk.com/>), [Jenkins](< https://jenkins.io/>) and others. I would very much like to update this article periodically, whenever I decide to add, remove or change something in my toolset, and why not, do some separate articles to communicate to you my findings. 

In the meantime, I’d really like to know what you are using and why, so I invite you to leave a comment and tell me. 

Until next time, stay curious!

