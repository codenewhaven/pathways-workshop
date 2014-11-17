# Welcome, Pathways Students!

Quicklinks within this document:

- [Welcome!](#welcome-pathways-students)
    - [Today's Agenda](#workshop-agenda)
    - [Your Instructors](#your-instructors-today)
    - [Examples! MBA Student Websites](#mba-student-websites)
- [Tutorial](#tutorial)
    - [Setup](#setup)
    - [Building Website](#building-website)
    - [Pushing Code](#pushing-code)

Thanks for coming to our workshop! You're here today because you want to learn
to code.

We only have two hours with you, so we won't be able to show you how to
build the next Facebook, but we will be able to show you that coding is
not as hard as you might think. By the end of the workshop, you should
having a working website that you can show to your friends and family.

Our goal is to give you the confidence that if you want to learn to code,
you can do it. It's not hard.

## Workshop Agenda

Start Time  | End Time| Content
------------- | -------------| -------------
3:00  | 3:15| Settle in, introductions, etc
3:15  | 3:45| Quick lecture, overview what you will do
3:45  | 4:00 | Break
4:00  | 5:00 | Build your website

Don't worry if this document looks really confusing! We are going to spend
the first 30 minutes showing you everything you need to do. Then, you're
going to do it! And we're here to help you, so we'll be walking around
between computers to answer any questions you have.

## Your Instructors Today
![Your Instructors](img/whobanner.png)

We started Code New Haven, which is an organization dedicated to teaching
high schoolers from New Haven how to code. This semester we have been
teaching a class at Metro Business Academy (MBA) how to code websites.

**PLEASE ASK US ANY QUESTIONS YOU HAVE! We're here to help you!!!**

## MBA Student Websites

Here are some of the websites the MBA kids have made!

- <http://laavila.github.io/>
- <http://creeperfan5236.github.io/>
- <http://spectryn.github.io/mywebsite%20copy%202.HTML>
- <http://mynamesmari.github.io/ImarisWebsite.html>
- <http://deondre.github.io/cubes.html>
- <http://maxjoyner.github.io/cubes.html>
- <http://brittneyfuller.github.io/>

They're a work in progress, but a great start! By the end of today, you're
all going to have a website like this.

# Tutorial

Don't worry if this all looks confusing. We're going to go over it with you
for the first 30 minutes, and then we're here to help.

The goal today is to build a website for yourself. Here's an example
of what you're going to build:

Here's an example of what you are going to build today:

- <http://codenewhaven.github.io/pathways-workshop>

In the next hour, this is what you're going to do:

1. Setup
    1. Create an account on **GitHub** (that's this website)

    2. Create a **GitHub repository** for yourself.

    3. **Clone** the repository, so you have a **directory** on your computer.

2. Building Webpage

    1. Create some **HTML files** in the repository.

    2. Open the HTML files in your browser -- that's your website!!

3. Pushing Code

    1. **Push the code to github** so anyone can see it! :)

If any of this looks confusing to you now, don't worry, it won't be soon!
It's actually all very simple.

### IF THIS LOOKS LIKE A LOT OF TEXT, DON'T WORRY!!
### You don't have to read all of it now. It might help you later.
### We are going to show you how to do everything you need to do.
### If you have questions, just ask us!

## Setup


## Building Webpage

A simple web page is just a file! When you use Microsoft Word to write a paper,
you are creating files. When you write an essay, you save it as something like
`myessay.docx`. When you save an image, you save it as `catpicture.gif` or
`funnyl0lz.jpg`. These are files. The important part of each file is the part
after the `.`, like `.docx`, `.gif`, or `.jpg`. This is called the
**file extension**, and it tells your computer what to do with the file. When
your computer sees a `.docx` file, it knows to open it in Word. Similarly, when
it sees a `.jpg` or `.gif` file, it knows to show you an image.

When you are writing a webpage, you want to use something called **HTML**.
HTML stands for "hypertext markup language", but you can think of it as
a very simple programming language. Any file ending in `.html` is an HTML
file, and your computer knows that **when it sees a `.html` file, it should
open it in your web browser.** That means that if you save a file as `index.html`
and double click it, your computer will open it in your web browser, e.g.
Google Chrome, Mozilla Firefox, or Microsoft Internet Explorer.

An HTML file looks like this:

(Don't worry -- you don't need to understand all of this!)

**/some/directory/on/your/computer/index.html**

    <html>
    <head>
        <title>Welcome to my website!</title>
        <style>
            body {
                background-color: #cecece;
            }
        </style>
    </head>
    <body>
        <!-- This is a comment. It won't show in the website because
             it has these arrows around it. -->

        <!-- Header text: <h1>...</h1> will make your text big -->
        <h1>Hi, welcome to my website!</h1>

        <!-- <p>...</p> stands for "paragraph" and puts space around
             the text you put inside it. -->
        <p>
            My name is Miles. Here's a picture of my friends:
        </p>


        <!-- This is how you insert an image. You need to make sure the
             filename in quotes exists. Here we have "friends.png" which
             is a file in the same directory as this. -->
        <img src="http://codenewhaven.github.io/pathways-workshop/friends.png" />

        <!-- This is another paragraph. -->
        <p>
            I hope we can teach you some cool things.
            For instance, check out this spinning cube!
        </p>

        <!-- Here's another paragraph. -->
        <p>
            <!-- And this is a link inside the paragraph. -->
            <a href="cube.html">Click here to see my cube!</a>
            <br />
            <a href="www.google.com">Or, click here to go to Google!</a>
        </p>
    </body>
    </html>

The code above is the source code powering the example website:

http://codenewhaven.github.io/pathways-workshop/

If you copy and paste that code into a file on your computer, and save it as
`index.html`, then you will see the same thing when you open the browser.



## Pushing Code
