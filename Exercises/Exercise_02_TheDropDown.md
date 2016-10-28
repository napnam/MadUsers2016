
Exercise 2 - The drop-down
===

Author:   Patrick Andriessen 
Version:  1.0
Date:     28-10-2016

# Goal
The primary goal for this exercise is to find and change the style of a drop-down using a text editor. The second goal for this exercise is to successfully add additional styles for the drop-down to the style sheet. 

# What will you learn
By doing this exercise you will learn that not all elements are already in your CSS file. You'll also learn how to style a drop-down effect.

# Caveat
Unlike the cross-reference, a drop-down might not already be present in your "MainStyles.css" file. You need to add the rules before you can start to style it. There are two ways to add the rules.

1. Find the rule in the MadCap Flare Styles Editor and change some styles. You'll find the code when you filter on Dynamic Effects Style. When you save the file and reopen it in your text editor you will see that there are now additional rules for the drop-down created.
2. Copy and paste the basic CSS rule manually in to the "MainStyles.css" file with your text editor. I've added the __standard__ rules below.

## Standard CSS rules for the drop-down text

```CSS
MadCap|dropDown
{
margin-bottom: 6px;
margin-top: 6px;
}

MadCap|dropDownBody
{
border-bottom: solid 1px#bed230;
}

MadCap|dropDownBody.Final
{
border-bottom: 0;
}

MadCap|dropDownHotspot
{
color: #404040;
font-size: 0.9em;
font-weight: bold;
}

MadCap|dropDownHotspot:hover
{
color: #5C258D;
}
```

## Styles associated with the drop-down

__MadCap|dropDown__ - This style affects the entire container holding a drop-down effect, including the image that is shown when a drop-down effect is open or closed.

__MadCap|dropDownBody__ This style affects the content that is shown when users open the drop-down effect

__MadCap|dropDownHead__ This style affects the entire container holding a drop-down hotspot (i.e., the paragraph where the drop-down link is located).

__MadCap|dropDownHotSpot__ This style affects the text in the first paragraph of a drop-downeffect that serves as the link for opening the drop-down body.

*You can change various properties too (e.g. the image next to the drop-down effect when it is open or closed), but that is for another workshop. You can find more information on properties in the Flares Style Guide.*

# The exercise

__Steps:__
1. Open the *Basic Steps.htm* topic (or a topic of your choosing) and create a drop-down text.
2. Build your target to see how your drop-down text looks.
3. Switch over to your text editor and open the *MainStyles.css* file.
4. Find the rules for the drop-down text (If you can't find them, read the Caveat paragraph).
5. Think of how you want to style your drop-down text (you're welcome to use pen and paper!) and change the CSS to reflect your design. 
6. Save your file and build your target. Look at the result.

NOTE: If you get stuck, dont worry. Try the inspirational CSS code provided below and start from there :) 

### Inspirational CSS code

```CSS
MadCap|dropDownBody
{
	color: #ffffff;
	width: 97%;
	background: #5C258D;
	-webkit-box-shadow: 0px 1px 3px #666666;
	-moz-box-shadow: 0px 1px 3px #666666;
	box-shadow: 0px 1px 3px #666666;
	margin-top: 5px;
	padding: 10px 20px 10px 20px;
}

```
===============================================================================