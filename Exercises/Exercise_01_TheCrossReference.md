
Exercise 1 - The cross-reference
===

Author:   Patrick Andriessen 
Version:  1.0
Date:     28-10-2016

# Goal
The primary goal for this exercise is to find and change the style of the cross-reference using a text editor. The second goal for this exercise is to successfully add an additional style for the x-ref to the style sheet. 

# What will you learn
By doing this exercise you will learn how to find your way in the "MainStyles.css" file, adjust the proper style and add an extra style so you can switch between styles from the Flare editor. This can potentially be a big time saver.

# Preparations
Create a new HTML 5 Top Navigation example project, just for this workshop, with the Start New Project Wizard.

# The exercise

## Primary exercise
__Steps:__
1. Open the *Basic Steps.htm* topic and create a cross-reference to one of the other topics.
2. Build your target for the first time to see how your cross-reference looks.
3. Switch over to your text editor and open the *MainStyles.css* file.
4. Find the rule for the cross-reference (Hint: look for the *MadCap|xref* selector).
5. Change the color of both the cross-reference and its hover effect.
6. Save your file and build your target. Look at the result.

## Additional exercise
__Steps:__
1. Switch over to your text editor and open the *MainStyles.css* file.
2. Find the rule for the cross-reference.
3. Add the Alternative CSS code (see below) after the closing } of the *MadCap|xref:hover* rule.
4. Save your file and switch back to Flare.
5. Open the *Basic Steps.htm* topic and create another cross-reference to one of the other topics. 
6. From the Styles pane select the new style for the cross-reference (it should look pretty red)
7. Build your target. Look at the result.

### Alternative CSS code

```CSS
MadCap|xref.alt
{
  background: #cd171a;
  background-image: -webkit-linear-gradient(top, #cd171a, #cc6e70);
  background-image: -moz-linear-gradient(top, #cd171a, #cc6e70);
  background-image: -ms-linear-gradient(top, #cd171a, #cc6e70);
  background-image: -o-linear-gradient(top, #cd171a, #cc6e70);
  -webkit-border-radius: 28;
  -moz-border-radius: 28;
  border-radius: 28px;
  text-shadow: 1px 1px 3px #666666;
  -webkit-box-shadow: 0px 1px 3px #666666;
  -moz-box-shadow: 0px 1px 3px #666666;
  box-shadow: 0px 1px 3px #666666;
  font-family: Arial;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  mc-format: '{para}';
  text-decoration: none;
}

MadCap|xref:hover.alt
{
  background: #36475a;
  background-image: -webkit-linear-gradient(top, #36475a, #868f98);
  background-image: -moz-linear-gradient(top, #36475a, #868f98);
  background-image: -ms-linear-gradient(top, #36475a, #868f98);
  background-image: -o-linear-gradient(top, #36475a, #868f98);
  text-decoration: none;
}
```
===============================================================================