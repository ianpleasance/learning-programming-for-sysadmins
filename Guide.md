V1.00 - 14/10/16

Learning Programming for Sysadmins

# Introduction - Why ?

Many sysadmins have years of scripting experience. Writing tools to help; install software, debug processes, manage log files, start and manage services, monitor performance, and handle other operational tasks is a standard part of a sysadmin’s job.

Normally these end up being written in bash, perl, or python and they work but are not particularly maintainable nor scalable. Learning programming can help improve your scripting and give you a wider choice of language and tools to write tools in.

In recent years the rise of Devops and the removal of the "gap" between the developer and the sysadmin means that sysadmins find themselves needing to learn to become more of a developer. 

Being a programmer rather than a scripter, and learning development workflows and practices means that you’ll be able to

* Better take part in Devops teams.

* Understand your developers’ requirements.

* Fix problems in code without having to "throw them back over the fence".

* Make things work in a more operational-way.

* Future-proof your career.

So as a sysadmin, how do you do this ?

# Thoughts and steps

* Think about where you want to end up.

Do you want to be a Developer, a Programmer, or a Computer Scientist ?
They aren’t the same thing, their definitions aren’t formal but [this article](http://www.skorks.com/2010/03/the-difference-between-a-developer-a-programmer-and-a-computer-scientist/) talks about why they do differ.

You don’t need to be a full-on Computer Scientist to be a good Programmer, but knowing some Computer Science theory is a good thing.

* Learn programming by building something you are interested in.

Find a personal need and code a tool or application to solve it. Having a deliverable will make it more interesting, and owning something will make you more likely to keep improving it as your knowledge improves.

* Scripting is NOT programming. 

Try and forget most of what you learned to do when scripting, don’t carry bad habits over.

* Do a beginner’s computer science course if need be.

You’ll already know the basics of sequence, selection, and iteration, but you want to shift your mindset to be that of a programmer not a scripter - and computer science courses will help with some of this transition. 

Plus you’ll also learn things that you might not have used before, for example; Recursion, Object Oriented Programming (OOP), abstraction.

* Learn one scripting language, e.g. Python, then learn one "true" development Language (Java, C, C++ for Enterprises, Go(Lang) for startup-type businesses).

Python is popular because it was the “new Perl”, it is a good replacement for Perl and Bash and it is the go-to language for system toolsmithing. 

However in my view it barely qualifies as a “real” programming language for a number of reasons; no true data typing, no real abstraction or polymorphism, the class model is crude, the random mixture of class methods, object methods, and libraries makes programming without an IDE unpleasant, its lack of a true pointer structure means that developing data structures (queues, deques, B-Trees, hash tables) is inefficient, and it encourages bad habits and the building of monoliths.

By all means start with it, but going on to learn a true strongly typed programming language that offers proper classes, objects, pointers, and strong data typing, will help you.

The chances are that the subsystems that you support will be written in C, Java, or C++ and so knowing them helps when debugging problems with them or needing to modify them and build them from source. 

And aside from Python these are the three most in-demand languages across the Enterprise side of the industry.

Outside of Enterprise sites, Go(Lang) and NodeJS could be better choices for secondary languages. Go is younger than Java/C/C++ but is more in-demand in start-up type sites and its use of memory, pointers, and objects is very C like.

Either way, once you’ve learned one development language then switching to another is typically very easy - so I wouldn’t get too hung up on which one to learn.

* Peer review, or pair, with someone outside of your team - ideally a developer not a sysadmin.

If you peer with another sysadmin then you’ll just encourage each other to do it the scripting way. Work with a developer and you’ll also pick up their mindset. But always ask them why they are doing things a certain way, it is the mindset that you really want to learn not the programming language.

* Look at your code with a critical eye, revisit it.

If you go back to it 1,3 and 6 months later, you’ll find opportunities for improvement.

* Use an IDE.

[IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)s aren’t essential, you can write good code without them, but things that you should be doing - for example making code into libraries - are easier with an IDE.

If using vi or emacs means it you take an hour to refactor code then you won’t do it, if using an IDE reduces that to 5 minutes then you will.

IDEs are like cars. Some IDEs work perfectly for many people but not others. Try different ones until you find one that works for you.

When you look at IDEs focus on ones that support multiple languages, it’ll make transitioning from one language to another easier if you don’t have to learn a new language and a new IDE at the same time.

Suggestions: 

* [JetBrains IDEs](https://www.jetbrains.com/products.html)

* [Jupyter](http://jupyter.org/) is somewhere between a training tool and an IDE, it allows you to run code interactively, support various languages, and many of the common libraries. It’s a great tool to learn a language with.

There is a good comparison of IDEs [here](https://en.wikipedia.org/wiki/Comparison_of_integrated_development_environments).

* Learn some basic algorithms.

You don’t need to be a Computer Science graduate to write good code, but learning basic algorithms like binary searches (rather than linear), hashing, and sort algorithms will help.

Also read [Why Sysadmins Can’t Code](http://cuddletech.com/?p=817) - despite its name it is actually a similar plan for helping Sysadmins become programmers and talks about some mindsets to avoid.

# Online training courses

*Free*

* [Sololearn](http://www.sololearn.com/) - Free iOS And Android apps for learning languages. 

Brief and basic, but you get a mini programming environment to try examples out in, quizzes and code segments to complete. 
Good if you know a number of languages and want to pick up a new one. I’m a big fan of their apps.

* [Coursera](https://www.coursera.org/) - Free Language and Computer Science training courses from universities. 

* [MIT Open Courseware](http://ocw.mit.edu/index.htm) - Free courses

* [EDX](https://www.edx.org/). Have some free courses, for example "[CS50: Introduction to Computer Science](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)"

* [CodeAcademy](https://www.codecademy.com/) - Free, Community based learning

* [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)

*Paid*

* [Udemy.com](http://www.udemy.com/) - Lots of decently priced courses and you can download them for offline use on their iOS/Android apps - ideal for commuting time. 

Courses tend to be language courses rather than Computer Science courses.
Just make sure you read the reviews of the courses as some are better than others -  anyone can upload a course to Udemy so the quality of instructors varies. 

* [Lynda.com](http://www.lynda.com/) - Has lots of training courses, they aren’t free but you do get a free trial.


# Improving your programming skills

* Put code on GitHub and collaborate.

Other people will take it and hopefully improve it. Don’t get defensive, use that as a learning opportunity.

* Try competitive programming.

[CodeWars](http://www.codewars.com/) - Gamified programming improvement. 

You get given challenges to solve, and once you’ve solved them then your solution is visible along with everyone else’s - people upvote the best, and seeing better solutions it is a great way of going from "this works" to “this is good code”. 

You can select “fundamental” level tasks or “training” level tasks - the latter watches the challenges that you solve and gives you gradually harder ones as you improve. 
I try and do one fundamental (as warm up) and one training task every other day.

I think this is a great way of improving. It can be a bit demotivating at first when you look at your code and the “best” solution side by side. However remember that there are multiple definitions of best... normally the best solution is the one that works for you and that others can easily read and maintain, using the “clever” features of a language is not always best. People focus on optimising code for speed, memory, i/o, etc - but optimising for support and readability is also perfectly valid so don’t get hung up on the fact that someone else wrote a solution using 2 lines less code but ended up with something hard-to-understand.

See also

[CodeCombat](https://codecombat.com/) - This is a very gamified (literally) programming site - it teaches computer programming by letting you design games.

[Codility](https://codility.com/programmers/) - Similar to the above two. This is a new one, I haven’t tried it yet.

[Stockfighter Trading](https://www.stockfighter.io/) - Develop your own stock trading algorithms in their sandbox.

[Project Euler](https://projecteuler.net/) - A large set of problems that can be solved in the language of your choice, great for code katas and pair programming.

* Learn some of the commonly used data structures and algorithms. 

If you need to do it, it has probably been done before by someone with huge math skills who is obsessed with making/improving an algorithm for it... 

Learning some of the commonly used algorithms stops you re-inventing the wheel and means that when programming you’ll think "Ah I can use a <blah> algorithm here".

For example

[Data Structures](https://en.wikipedia.org/wiki/List_of_data_structures): Linked Lists, Stacks, Heaps, Deques, Graphs, Binary Trees, Hash Buckets

[Algorithms](https://en.wikipedia.org/wiki/List_of_algorithms): Binary (Chop) Search, Quicksort, Tree Traversal, Djikstra’s algorithm

* Review your code and think about it from a scaling perspective.

Read up on algorithmic measurement, [space/time complexity](https://en.wikipedia.org/wiki/Time_complexity#Table_of_common_time_complexities), learn "[Big O" notation](https://en.wikipedia.org/wiki/Big_O_notation#Use_in_computer_science).

When you are programming think about whether your code would work if its input data set was increased by a factor of 10000. 

Doing this could make the difference between your code being long-term usable and you having to quickly rewrite it under pressure because the runtime suddenly went up by 10 times because you tripled the size of the input.

Big O is a way of measuring the scaling factor for an algorithm, which gives you a way to compare algorithms and to gauge how your code would scale. 

There are some beginners primers on Big O [here](https://justin.abrah.ms/computer-science/big-o-notation-explained.html), [here](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/) and [here](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity), and a algorithm/structure->complexity cheat sheet [here](http://bigocheatsheet.com/).

* Read programming interview sites.

You don’t need to be job-hunting to practice for programming interviews, interview sites will provide you with programming challenges that might include areas which you don’t normally work on.

[https://www.interviewcake.com/python-interview-questions](https://www.interviewcake.com/python-interview-questions)

Some python interview questions

interviewcake.com also have a [mailing list](https://www.interviewcake.com/free-weekly-coding-interview-problem-newsletter) you can sign-up for to receive a weekly programming challenge. 

[https://esalagea.wordpress.com/category/cracking-the-coding-interview-a-python-experience](https://esalagea.wordpress.com/category/cracking-the-coding-interview-a-python-experience)/

Challenges from the book "Cracking the Coding Interview"

[https://www.careercup.com/page?pid=python-interview-questions](https://www.careercup.com/page?pid=python-interview-questions)

Some python interview questions

[http://javarevisited.blogspot.co.uk/2015/01/top-20-string-coding-interview-question-programming-interview.html](http://javarevisited.blogspot.co.uk/2015/01/top-20-string-coding-interview-question-programming-interview.html)

Some programming interview challenges, mainly string related.

[http://www.mypythonquiz.com/question.php](http://www.mypythonquiz.com/question.php)

A python Quiz

* MeetUps.
There are loads of these now, particularly for the more "trendy" languages - Go(Lang), Scala, Clojure, etc.

# Books

* [The Art of Computer Programming](https://en.wikipedia.org/wiki/The_Art_of_Computer_Programming)

It can be dry, but Donald Knuth’s series has been one of the classic references for many many years.

* [Introduction to Algorithms](https://en.wikipedia.org/wiki/Introduction_to_Algorithms)

Thomas Cormen, Charles Leiserson, Ronald Rivest, Clifford Stein

* [Programming Pearls](https://reprog.wordpress.com/2011/04/18/programming-books-part-5-programming-pearls/)

Jon Bentley

* [The Mythical Man Month: Essays on Software Engineering](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)

Fredrick P. Brooks

This talks more about the practice of software engineering process and project management, but it is a good read.

* Structure and Interpretation of Computer Programs (2nd Edition)

Harold Abelson and Gerald Jay Sussman.
This is a popular source book for Computer Science classes, but note that it teaches using Scheme - which is not the most accessible language.

* Design Patterns: Elements of Reusable Object-Oriented Software

Erich Gamma, Richard Helm, Ralph Johnson, and John M. Vlissides
A popular book for teaching Object Oriented programming, however note that it teaches using C and Smalltalk

* The Pragmatic Programmer: From Journeyman to Master

Andrew Hunt and David Thomas
A decent book for improving programming practices.

# TL;DR

* Do a online basic computer science or programming course.

* Install an IDE and get comfortable with it.

* Learn something like Python, then move onto Java,C or C++ or Go(Lang)

* Find a developer and pair with them.

* Sign up for CodeWars and learn to improve your code.

* Read a book or article on the craft of programming/programming practices

* Learn to programme for scale

