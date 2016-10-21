slidenumbers: false
autoscale: true

# [fit] MadUsers 2016
## [fit] Venture outside of the *CSS* comfort zone

Patrick Andriessen
napnam Publishing & Consulting

![right](_assets/MadUsers_txt.png)

---

# [fit] Hello! 
# [fit] How are you doing?

---
# Who am I? Here is some trivia
My name is Patrick 

I'm from the Netherlands

I am a freelance consultant

---
# [fit] Today 
We are going to be manipulating the stylesheet of a MadCap Flare project, but we are *__not__* going to use Flare[^1] to do it. 

[^1]: Actually we are going to use Flare, but only to build our target.

---

# So what are we going to use?
Well, we are going to use a text editor to mmanipulate Flare styles.

---
For the love of *[insert favorite deity]*
# [fit] Why!?
---
There are a couple of reasons why you would like to use a external editor...

1. It is fast
2. You learn a lot about CSS and HTML by looking at the code
3. You can do stuff, you can't do in the Flare editor
4. Did I mention it is fast?

---
After this little expedition outside of your CSS comfort zone, you will feel like...

---

![fit](http://i.giphy.com/12UlfHpF05ielO.gif)

---
# [fit] What do you need?
---

##What do you need?

* A laptop with Flare installed and running (pref. v12)
* A text editor 
(notesblok or notepad will do for now[^2])

[^2]: I like to use a more advanced editor, especialliy one that supports syntax highlighting

---
=======
![fit](example.png)

---

^This slide is about changing the x-ref styles outside of the stylesheet editor.

## The X-Ref
In Flare we use the x-ref for linking to other content in- and outside of the Flare project.

---

## The X-Ref (default styling in style editor)

PICTURE HERE

---
## Where is the css code located?
The CSS 

---

## The X-Ref (default styling in css file)
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

## The X-Ref (fancy styling)
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
* Step 1 - Open the *Basic Steps.htm* topic
* Step 2 - Create a X-ref to the *Feature1.htm* topic

---

## The Drop-down
In Flare we can use drop-downs to make content appear at the click of a buttom (or thumb).

---

## Tables
To present data there is nothing like a fine table.

---

# [fit] Resources
Ready to start tinkering? Here are some great places to start!

---

## Text editors
[*Sublime Text 3*](https://www.sublimetext.com/) - win & mac (paid)
https://www.sublimetext.com/

[*Notepad++*](https://notepad-plus-plus.org/) - win (free)
https://notepad-plus-plus.org/

[*Atom*](https://atom.io/) - win & mac (free)
https://atom.io/

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

__[Twitter](https://twitter.com/napnamPat)__, __[GitHub](https://github.com/napnam/MadUsers2016)__ *and* __[Slack](https://madusers.slack.com)__.

---

# [fit] __Tak!__
# [fit] Thank you!
# [fit] Dank jullie wel!

---
# [fit] Contact information

Patrick Andriessen
napnam Publishing & Consulting

www.napnam.nl
patrick@napnam.nl
@napnamPat

