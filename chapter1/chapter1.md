# **Hellow World**

## **CSS in Modern Front-end Development**
***The creation and maintenance of our projects on the Web has advanced as the Web
has progressed. Where we were once perhaps webmasters, the many, varied disciplines involved in making websites and applications has diversified. Front-end development is now one of many roles required in making today’s websites. A frontend developer will generally now produce HTML, CSS, and JavaScript for a web
application or site so that its visitors can access the content and interact with it.***

***With modern websites providing more content in various ways and with most web
makers adopting an approach that incorporates responsive web design principles,
we’re now writing more complex CSS than ever before. Add to that how CSS is an
ever-changing language, with more and more features added to its existing set every
year.***
***CSS practices and methodologies such as OOCSS1, SMACSS2, ITCSS3, and BEM4
(to name but four) are excellent tools and processes that help with writing stylesheets
and keeping us sane in this modern era of front-end development. Yet, creating CSS
for a responsive, device-agnostic website using OOCSS and BEM can lead to thousands of lines of code in one cumbersome file.***

***We will soon explore how Sass can help you with this. But if you happen to be a
total beginner on the matter, you might even be wondering …***


## **What is Sass?**
**Sass is a stylesheet language that is an extension of CSS. It is one of a few preprocessors (more on that in a bit) available to the front-end developer. As it has been
around the longest (of the aforementioned preprocessors), we could agree with the
official website5 when it reports to be the “most mature, stable, and powerful professional-grade CSS extension language in the world.”***

***Using Sass helps eliminate some of the monotony and overhead from writing CSS.
No longer will you have to remember that specific hex color code for the company’s
brand. Say goodbye to one long CSS stylesheet or additional HTTP requests, as well
as increased page load times by splitting up your CSS files to several files such as
reset.css, mobile.css, tablet.css, desktop.css and print.css. Want an easier way to write
CSS media queries? Sass has you covered. Like using ems or rems but hate working
out the math? Sass can help you.***

***All in all, we can safely state that Sass will make it easier for you to develop websites
and web applications—benefiting you, your client, and your clients’ users. Keep****
***your work in check and minimize opportunities for broken designs using the power
of Sass.***

***Sass may have its downfalls but, generally, problems that developers find with Sass
are usually when they struggle to understand some aspect of it. With this book, we
hope to give you the building blocks to write awesome Sass code. But you will require a firm grasp of CSS as well; if you write bad CSS in the first place, you’ll end
up writing bad Sass too. You might be familiar with the saying “Tools do not output
bad code. Bad developers do.” Remember, Sass is just a preprocessing tool, which
leads us to our next section.***



## **What is preprocessing?**
***As mentioned, Sass is a preprocessor. It takes Sass (.sass) or SCSS (.scss) files as
input, and outputs CSS files (.css). Sass adds a lot of great features that can help
to create better stylesheets, but as you know, web browsers only understand CSS,
not Sass. What we do is write our CSS (with as much a sprinkling of Sass as needed)
in .scss or .sass files in our code editor, and then have Sass compile that into a .css
file for the browser to read.***

***Using a preprocessing language such as Sass means we’re not bound within the
limitations of CSS. Sass can—and does—add features that enhance our writing of
CSS; however, it does not—and cannot—add features to CSS itself. It’s vital that
you grasp this from the outset.***
```sass

```


## **The Tale of Two Syntaxes**
***When talking about Sass, we usually refer to the preprocessor and the language as
a whole; for example, a Sass project, or a Sass variable. Meanwhile, Sass (the preprocessor) allows two syntaxes:***

1. **Sass, also known as the indented syntax**
2. **SCSS, or Sassy CSS, a CSS-like syntax**


***Let’s pause for a moment for a short history lesson. Initially, `Sass` was part of another
preprocessor (that still exists) called Haml6, which was heavily inspired by the
programming language `Ruby`. Sass stylesheets used a Ruby-like syntax with no
braces or semicolons, and a strict indentation:***

![](img/1.png)

***This was up until 2009, when the new .scss file format was introduced that adhered
more closely to the usual CSS syntax. The rule of thumb here is if it is valid CSS,
it’s valid `SCSS`:***

![](img/2.png)

***As to which syntax to use, the choice is really up to the author as both are strictly
equivalent in features. The Sass indented syntax is shorter and lighter to type because
almost all punctuation is gone, but it’s also incompatible with default CSS syntax.
It would appear that SCSS is the most popular in the Sass community as it is closer
to CSS and has an easier learning curve, contrary to the whitespace-sensitive syntax
4 Jump Start Sassof Sass. Because of this, we’ll be using SCSS in the code displayed throughout this
book.
Note that “Sass” is never uppercase, no matter whether we’re talking about the
language or the syntax. Meanwhile, “SCSS” is always uppercase. You could use
http://SassnotSASS.com/ as a reminder.***

![](img/3.png)
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```


## ****
******
```sass

```






