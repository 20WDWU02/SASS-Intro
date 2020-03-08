# SASS: Syntactically Awesome Style Sheets

> Sass is a CSS preprocessor, which adds special features such as variables, nested rules and mixins into regular CSS. 

For the rest of this module, we won't be writing any more pure CSS, but rather writing SASS which will convert into CSS.  
At this stage, we will be using [Koala](http://koala-app.com/) to compile out SASS into CSS.

## Koala Settings
Before we process too much, there are a few settings we want to change in Koala to help us use SASS easier. You want to do this before you open your first sass project and the settings should save for future projects.  

Once you have opened Koala, click the cog icon in the top left.  
Under General you want to
* Turn on 'Notification when comiple is completed'. 
* Turn off 'Automatically compile when project is added or reloaded'.  

This will give us a notification if we get a successful compile, or an error is something went wrong, and will prevent koala from automatically compiling our code when we add a project so it doesn't compile in the wrong place.  

Under Sass you want to
* Turn on Autoprefix
* Select your Output Style to expanded.

Once you have changed those settings, you can drag over your project folder where Koala will find any files it can manipulate, ours should be at least our .scss files. Make sure to check where the output path goes to as this Koala will guess where you want your .css file to go.

## .scss
Rather than making .css files we will now be creating **.scss** files. This is the file extension for writing sass. Often these will be located in a **sass** folder in the root of our directory.  

In this file, we can write normal CSS and if your output path is pointing to the right directory, whenever you save the file it should create/override the .css with your newly created code.
