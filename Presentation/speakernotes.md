^ My name is Patrick. I'm from the Netherlands. I am technical information consultant. This is my first public speaking gig in quite some time. And I'm not nervous. At all.


# Today 
We are going to work on the MadCap Flare project styles, but we are *__not__* going to use Flare to do it. 

We still need Flare, but only to edit our topics and build our target to see the result of our work.

# Workshop agenda

1. Some background information
2. Exercise: __The X-ref__
3. Exercise: __Tables__
4. Exercise: __The Dropdown__
5. Evaluation

# So what are we going to use in stead of Flare?
Well, we are going to use a text editor to work on Flare styles.

"For the love of *[insert favorite deity]*"
*Why!?*

# Reasons
There are a couple of reasons why you would like to use a text editor...

1. It is fast (when you get used to it)
2. You learn a lot about CSS and HTML by looking at the code
3. You can do some pretty cool stuff, you can't do with the Flare editor
4. Did I mention it is fast?

And after this little expedition outside of your CSS comfort zone, you might feel like...

![right](http://i.giphy.com/12UlfHpF05ielO.gif)

# What do we need?

* A laptop with Flare installed and running (pref. v12 or v11)
* A text editor (notesblok / notepad will do)

I like to use a more advanced editor, especialliy one that supports syntax highlighting.	
---
# Exercises 

## Exercise 1: The X-Ref
In Flare we use the x-ref for linking to other content in- and outside of the Flare project.

### The X-Ref (default styling in style editor)

![inline fill 75%](_assets/MainStyles_LinkStyles.png)

### Where is the css code located?

![inline fill 90%](_assets/LocationStyles.png)

### The X-Ref (default styling in css file)
```
MadCap|xref
```
```css
 {	
 	color: #2D8DCC;
 	font-weight: bold;
 	mc-format: '{para}';
 	text-decoration: underline;
 }

```
---

### The X-Ref (fancy styling)
```
MadCap|xref
```
```css
{
	background: #3498db;
	background-image: -webkit-linear-gradient(top, #3498db, #2980b9);
	background-image: -moz-linear-gradient(top, #3498db, #2980b9);
	background-image: -ms-linear-gradient(top, #3498db, #2980b9);
	background-image: -o-linear-gradient(top, #3498db, #2980b9);
	background-image: linear-gradient(to bottom, #3498db, #2980b9);
	-webkit-border-radius: 28;
	-moz-border-radius: 28;
	border-radius: 28px;
	font-family: Arial;
	color: #ffffff;
	font-size: 20px;
	padding: 10px 20px 10px 20px;
	text-decoration: none;
	mc-format: '{para}';
}
```
---
## Exercise 1 - Modify the CSS for a X-ref
### Prep
1. Open the *Basic Steps.htm* topic
2. Create a X-ref to the *Feature1.htm* topic
3. Open the main stylessheet

---

## The Drop-down
In Flare we can use drop-downs to make content appear at the click of a buttom (or thumb).

---

## Tables
To present data there is nothing like a fine table.

---

# Evaluation

<br>
1. Would you consider using a text editor for your own projects in the future?
2. Why would you use or not use a text editor for your own projects?


---

# [fit] Resources
Ready to start tinkering? Here are some great places to start!

---

## Recommended text editors
[*Sublime Text 3*](https://www.sublimetext.com/) - win & mac (paid)
https://www.sublimetext.com/

[*Atom*](https://atom.io/) - win & mac (free)
https://atom.io/

[*Notepad++*](https://notepad-plus-plus.org/) - win (free)
https://notepad-plus-plus.org/

---

## Learn more about CSS

[*CSS: The Definitive Guide, Fourth Edition*](http://meyerweb.com/eric/thoughts/2012/10/01/csstdg4e/) (book)
http://meyerweb.com/eric/thoughts/2012/10/01/csstdg4e/

[*CSS: The Missing Manual by David Sawyer McFarland*](https://amzn.com/1491918055) (book)
https://amzn.com/1491918055

[*Learn to Code HTML & CSS, created by designer & front-end developer Shay Howe*](http://learn.shayhowe.com/html-css/) (course)
http://learn.shayhowe.com/html-css/

[*Advanced CSS: Best Practices for Formatting Notes, Tips, Cautions and Warnings in MadCap Flare" webinar*](http://www.madcapsoftware.com/demos/player.aspx?v=d01db2694e8e6) (webinar)
http://www.madcapsoftware.com/demos/player.aspx?v=d01db2694e8e6

---

# [fit] Join __me!__
My name is *Patrick Andriessen* and you can find me on: 

* [Twitter as @napnamPat](https://twitter.com/napnamPat)
* [GitHub - https://github.com/napnam/MadUsers2016](https://github.com/napnam/MadUsers2016)
* [Slack - https://madusers.slack.com](https://madusers.slack.com)


The slidedeck and materials used in this workshop are available for download. 
Just go to:

_[http://www.napnam.nl/madusers2016](http://www.napnam.nl/madusers2016)_

---

# [fit] __Tak!__
# [fit] Thank you!
# [fit] Dank jullie wel!

---
# [fit] MadUsers 2016
## [fit] Venture outside of the *CSS* comfort zone

__Patrick Andriessen__
*napnam Publishing & Consulting*	

@napnamPat
patrick@napnam.nl

www.napnam.nl/madusers2016

![right](_assets/MadUsers_txt.png)





