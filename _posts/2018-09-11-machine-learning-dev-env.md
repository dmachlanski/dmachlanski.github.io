---
layout: post
title: "Python for Machine Learning - setup your tools"
excerpt: "How to prepare your development environment for Python and Machine Learning quickly"
---

Okay, you want to play around with some Machine Learning stuff using Python, but you are not sure how to setup your environment. There are so many tools to choose from. I’ve recently come across a similar situation and gone through some issues. This hopefully save you some time or help make a decision.

## Python environment
Basically, there are two main options:

1.	Get a pure [Python](https://www.python.org/downloads/) installation. Try to use pip to acquire all the libraries you want. Get stuck because of conflicting dependencies, versions etc. Spend many hours on stackoverflow and Python related sites to find a solution. Get tired.
2.	Just install [Anaconda](https://www.anaconda.com/download/).

Seriously, give yourself a favour and install that Conda. Trust me. It comes with a ton of data science libs straightaway and all works perfectly fine right after the installation. Just install and use!

I am not saying this cannot be done via a pure Python way. I just mean you can save lots of time. If you like tinkering and scratching your head for hours – go ahead.

Last tip: If you are aiming to use the latest libs and "bleeding edge", state-of-the-art algorithms - choose version 3.x. If you are not sure - pick 3.x.

### Further updates and installations
At this point I am assuming you have chosen Anaconda (c'mon!). Sooner or later you will most certainly stumble upon an interesting library that you would love to try but it is not a part of the standard Conda setup. In this case the conda command line tool is your friend. But first go [here](https://anaconda.org/) and search for the lib you are looking for. Then, somewhere at the bottom, you should see a cmd line - copy&paste to your cmd/powershell and execute. Boom! You have a new package installed! :D

You may also want to run the following command from time to time, just to make sure your packages are up-to-date:
`conda update --all`

This will show outdated packages:
`conda search --outdated`

## Writing code
Well, we have to actually write somewhere! I personally distinguish two types of workflow:
- Writing a complete application from start to end
- Experimenting with new ideas, learning new concepts or libraries

### Complete app
In this case I prefer [VS Code](https://code.visualstudio.com/). It is free, lightweight and minimalistic. Just install Python extension and you are ready to go!

If your only religion is full-fat Visual Studio, you are not lost. You can install Python tools extension and fight from there. I actually have given it a quick try as I use VS for software development on daily basis. I was positively surprised by project templates and debugging features. I believe this is a nice choice as well.

### Experimenting
For this sort of activity I think the ideal candidate is [Jupyter Notebook](http://jupyter.org/). It comes together with Conda installation. There are plenty of benefits here, you can mix together your code and formatted text, plot charts, execute small parts of code and many more. I cannot stress enough how useful it has become for me. Now, I cannot imagine using a different tool for this type of work and lately I've been using this even more than VS Code!

## You are ready to rock!
Brilliant, you are all set! Now, grab some tutorials or go straight and implement your ideas!

Good luck!

Damian M