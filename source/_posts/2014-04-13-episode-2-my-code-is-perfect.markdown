---
layout: post
title: "Episode 2: My Code is Perfect"
date: 2014-04-14 07:00
comments: true
categories: Clean Code
---
Writing clean code isn't something you pick up overnight, nor is it a brand new topic. In this episode Jeff and Matt discuss the characteristics and mechanics of creating clean code and how to approach your project from a clean code perspective.

{% raw %}
<iframe src="http://media.signalleaf.com/player/Loosely-Coupled/53497613eda3b00200000006/" width="500" height="70" frameborder="0"></iframe>
{% endraw %}
[Download](http://media.signalleaf.com/Loosely-Coupled/53497613eda3b00200000006/LooselyCoupled-Episode2-MyCodeIsPerfect.mp3)

### Notes

In this episode, Jeff and Matt talk about code quality and beautiful code. Beautiful code follows a standard. If you don’t have one, find one and adopt it. For PHP projects you can start with PSR-2, a part of the <a href=“https://github.com/php-fig/fig-standards”>PHP-FIG Standards</a>, or PSRs (not actually called <a href=“https://twitter.com/jcarouth/status/445892760256528384”>Phil’s Silly Recommendations</a>.)

Find a project you can admire–or at least one that has the quality level you want to achieve–and study it. One example might be to look at a framework that’s popular, such as <a href=“https://github.com/laravel/laravel”>Laravel</a>. Study the project and realize that it likely didn’t come to exist exactly how it is now overnight.

Don’t be afraid to throw code away. Your first solution will never be the best solution to the problem. It’s okay to write code to learn more about your problem–perhaps just tests, even–and then get to a reasonably-clean solution eventually.

While Jeff and Matt talk a lot about coding standards, there is much, much more to clean code. The three holy books of clean code are <a href=“http://www.amazon.com/dp/0132350882/”>Clean Code: A handbook of Agile Software Craftsmanship</a> and <a href=“http://www.amazon.com/dp/B0050JLC9Y/”>The Clean Coder: A Code of Conduct for Professional Programmers</a> by Robert Martin (a.k.a. Uncle Bob,) and <a href=“http://www.amazon.com/dp/0735619670/”>Code Complete: A Practical Handbook of Software Construction</a> by Steve McConnell. Reading these three books won’t necessarily make your code better, but it certainly won’t hurt you to be aware of what they contain.

Learning the process of writing clean code takes an entire career. Matt watched a relevant TED talk about the technique of learning things in 20 hours called <a href=“https://www.youtube.com/watch?v=5MgBikgcWnY”>Learning Anything in 20 Hours</a>. To become great at doing anything as a programmer, you have to learn the process of breaking your subject up into segments and practice. It’s Matt’s opinion that the idea of taking 10,000 hours to master something is too daunting, so breaking things up into 20-hour segments is more appealing.

On the subject of practicing, one useful tool for practice is a <a href=“http://en.wikipedia.org/wiki/Kata_(programming)”>Code Kata</a>. There is a formal definition and lots of resources for code katas. But what if you could just apply the concept of repetitive practice into your tasks? Matt did something like this with an OAuth 1.0 client he was working on to learn about signatures.

There is no substitute for actually writing code. No amount of reading documentation will substitute for experiencing the errors that come about from your misunderstandings. It is part of the process.

Being a sole developer is hard in terms of code quality. You need someone else to look at your code because that exposes the problems with the legibility of the code you’re writing. So if you are a sole developer, find some way to get someone else’s eyes on your project. No one will know if your code is good or bad if they can’t see it. Posting small gists or pastebins is not sufficient.

Ship early, ship often. If your code is only local, no one can help you. Get your code out there as soon as possible. You’ll be a better developer because of it.

Jeff and Matt weigh in on developing libraries for a larger audience. You should start by solving an actual problem in your business, then extract into a library if it’s relevant outside of your business. Don’t start out with the goal of making the new hotness, let that come naturally. Matt mentioned his <a href=“https://github.com/mfrost503/Snaggle”>Snaggle</a> library as something he’s working on right now and Jeff mentioned a project he worked at for his employer called <a href=“https://github.com/liftopia/clerk-gem”>the Gem formerly known as Clerk</a>. Both of these started as libraries which kind of contradicts this advice.

If you’re looking for a HTTP client for your PHP projects, look no further than <a herf=“https://github.com/guzzle/guzzle”>Guzzle</a>.

The last important point of discussion is to always challenge your expectations and assumptions in your code. When you’re writing code you should be constantly asking yourself, “why am I doing it this way?” Sometimes the answer is, “I don’t know,” which means you need to take a break and seek out the answer to the question.

Go forth and practice writing clean code.
