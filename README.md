# Xcode

## Overview

In this lesson, we'll take a deeper dive into Xcode. 

## Learning Objectives

* Describe how Xcode allows for the creation of various iOS and Apple applications
* Distinguish the four main areas of Xcode and how to find information printed to Console Output Viewer
* Run a simple application in Xcode

## What is Xcode?

There are iPhones, Macs, Apple Watches & Apple TV's which represent the hardware offered by Apple. Powering these various devices is software. There are different pieces of software deployed on each device, names you might already be familiar with.

* iOS, MacOS, tvOS, watchOS

Being a developer, you will want to create various applications for these various operating systems (everyone has an app idea). 

There needs to be a place where we can create this software. We use a Word document to create essays, stories, and other text based documents. 

Xcode serves as our Word document. It's a place where we write code.

The programming languages we can utilize within Xcode are Swift & Objective-C. When this code is written, we can then *run* the application. When doing so, Xcode is able to take the code we wrote and read it. It does more than read the code, it's able to compile it and allow any of the above devices to run it!

This process described above is known as an Integrated Development Environment, or IDE. Xcode then is the IDE provided by Apple that allows us to create apps.

![Xcode](http://i.imgur.com/H5IUNEe.png)

Let's dive into some step-by-step specifics. Here we're opening up Xcode and starting a new project. We have the ability to begin an iOS, watchOS, tvOS or MacOS (here it's still OS X) application. It's that simple.

We can hit next and create our project. We will be asked to provide the name of our app.

![example](http://i.imgur.com/MHcgw8r.png)

After hitting next, we can begin to write our code! The language we're using here will be Swift.

![locate](http://i.imgur.com/WGqFvDu.png)

We've selected the `ViewController.swift` file in the left pane. By doing this, this brings up a document in the center (main) window where we can now write some code!

Here's an example of some code in this `ViewController.swift` file.

![ex](http://i.imgur.com/WvSiOB0.png)

So now that we've written some code in this `ViewController.swift` file, how do we make it *run*. 

In the upper left corner of Xcode, you should see what appears to be a Play Button with a Square (stop) button to the right of it. If you were to click the Play button, your app will run! So lets do that.

![runn](http://i.imgur.com/y8Mp5FA.png)

'Hello everyone' was printed to the console here.

You should have also noticed, that something else appeared on screen when you ran your app.

![simulator](http://i.imgur.com/7JxaDCZ.png)

This is the Simulator. It simulates what your app will look like. That way, you aren't required to plug and run your app on your iPhone when developing an app. We can do so right from our computer. 

Let's change the background color to blue.

![blue](https://s3.amazonaws.com/learn-verified/StringSwiftBlue.png)

After including this code, if we were to run our app (You can also do this pressing command + r) - the simulator should look like this:

![bluee](http://i.imgur.com/zjyrEaw.png)

This is the process of creating an app.


**Note:** *The first time you open Xcode, your machine will ask you if you want to enable "Developer Mode". Go ahead and do this; don't be scared of it! What it does is allow you to debug your projects without OS X asking for your administrator password every time. If you previously selected "No" the first time that you opened Xcode, don't worry! Just open your terminal and type* `$ DevToolsSecurity -enable`.

## Xcode Areas

![xcodeThing](http://i.imgur.com/tNpTjA3.png)

The workspace window always includes the editor area. When you select a file in your project, its contents appear in the editor area, where Xcode opens the file in an appropriate editor. For example, in the figure above, the editor area contains AdventureScene.swift, a swift code file that is selected in the navigator area on the left of the workspace window.

The workspace window displays up to three optional areas used in performing different tasks in the development life cycle. Hiding areas not in use can help you focus on your current task. You can hide or show these optional areas by using the workspace configuration buttons on the far right side of the toolbar:

![nav](http://i.imgur.com/oxJnlOP.png)  Show and hide the navigator area. Use this area for navigating all facets of your project, including files, symbols, breakpoints, build issues, tests, breakpoints, and build reports. You can also search for any string in your project.

![debug](http://i.imgur.com/jQ22SM6.png)  Show and hide the debug area. Use this area for viewing variables, interacting with the debugger console, and controlling the execution of your app.

![rightThing](http://i.imgur.com/BZ0INGj.png)  Show and hide the utilities area. Use this area to inspect or modify attributes of files, graphical user interface elements, sprites, and other elements in your project. Also use it to access a library of ready-made resources. See Accessing Resources and Inspecting Elements.

![](https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_toolbar.png)

The Toolbar is a small collection of project-wide buttons and labels. They are:

1. Close/Minimize/Maximize Window buttons (these are the red, yellow, and green dots standard to all OS X windows),
2. The ▶︎ "**Run**" button (`⌘` `R`) which builds and then runs the current scheme,
3. The ◼︎ "**Stop**" button (`⌘` `.`) which stops the running scheme or application,
4. The "**Scheme Menu**",
	* The left half selects the current target,
	* The right half selects the destination—the device or simulator you wish to run on, (**Note:** *If you connect an iOS device to your computer, Xcode will typically assume you want to run the build on that device and automatically select it as your destination. If you encounter an authorization error, this may be the cause of it. Selecting the simulator instead will not trigger the authorization check.*

5. The "**Activity viewer**" displays information relevant to the current operation, as well as symbols for the number of warning and errors generated by the compiler,
6. The **Editor configuration buttons**,
	* "**Standard Editor**" - shows the primary code editor window
	* "**Assistant Editor**" - shows a secondary code editor window alongside the primary window (this gets crowded without a larger screen),
	* "**Version Editor**" - shows the Xcode's built-in version control UI, since we utilize git and GitHub for version control, you will not use for the labs,
	
7. The **Workspace configuration buttons** which show or hide their respective areas:

| Icon            | Workspace Configuration Button      |
|:---------------:|-------------------------------------|
| ![][nav_left]   | Show or hide the **Navigator area**.|
| ![][nav_middle] | Show or hide the **Debug area**.    |
| ![][nav_right]  | Show or hide the **Utilities area**.|

---


[nav_left]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_left.png
[nav_middle]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_middle.png
[nav_right]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_right.png



<p data-visibility='hidden'>View <a href='https://learn.co/lessons/reading-ios-intro-to-xcode'> Xcode: Just Enough</a> on Learn.co and start learning to code for free.</p>
