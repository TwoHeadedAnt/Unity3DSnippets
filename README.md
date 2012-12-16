# Unity3D Snippets and Completes
#### for [Sublime Text 2](http://www.sublimetext.com/2)

## About
This is a fork of micael bergeron's fork of Jacob Pennock's Sublime Text 2 package, which adds a number of helpful snippets and completes for working with Unity3D.

## Usage
A number of useful snippets have been added. Please take a look at the LIST.MD for an alphabetical list of all the additions.
However, we've barely begun scratching the surface of the Unity Script Reference, so please help out!

If you're keen on adding more snippets or commit other changes, go ahead and fork this repository.

### Snippet formatting
For my own additions, I've used the following formatting:
#### File name
FUNCTIONFAMILY-Function.sublime-snippet (e.g., TIME-deltaTime.sublime-snippet).
#### Snippet structure
 * the tabTrigger consists of the first three letters of the function family, and then the first letter of each word in the function name.
The tabTrigger for the above deltaTime example would look like this: <tabTrigger>timdt</tabTrigger>.
 * the description shows the function and its parameters first, followed by an optional detailed description. 
Example: <description>Input.GetAxisRaw(""). Returns the value of the virtual axis identified by axisName with no smoothing filtering applied.</description>

## Install

### Package Control

The easiest way to install this is with [Package Control](http://wbond.net/sublime\_packages/package\_control).

 * If you just went and installed Package Control, you probably need to restart Sublime Text 2 before doing this next bit.
 * Bring up the Command Palette (Command+Shift+p on OS X, Control+Shift+p on Linux/Windows).
 * Select "Add Repository". Insert the URL of this fork: https://github.com/TwoHeadedAnt/Unity3DSnippets
 * Bring up the Command Palette again and select "Install Package".
 * "Unity3D Snippets and Completes" should appear in the list. Install it.
 * If the snippets do not appear to work, the package might have been put in "ignored_packages". Go to Preferences / Settings - User, remove any relevant entry in "ignored_packages".

