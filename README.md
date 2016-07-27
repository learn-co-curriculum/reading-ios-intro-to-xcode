# Xcode: Just Enough

## Objectives

1. Get acquainted with Xcode just enough to start playing with Swift.
2. Distinguish the four main areas of Xcode and how to find information printed to Console Output Viewer.
3. Say hello to the iOS Simulator.

## What is Xcode?

There are iPhones, Macs, Apple Watches & Apple TV's which represent the hardware offered by Apple. Powering these various devices is software. There are different pieces of software deployed on each device, names you might already be familiar with.

* iOS, MacOS, tvOS, watchOS

Being a developer, you will want to create various applications for these various operating systems (everyone has an app idea). 

There needs to be a place where we can create this software. We use a Word document to create essays, stories or... I'm not really sure, I don't use Word documents anymore but you get the point.

Xcode serves as our Word document. It's a place where we write code.


The programming languages we can utilize within Xcode are Swift & Objective-C. When this code is written, we can then *run* the application. When doing so, Xcode is able to take the code we wrote and read it. It does more than read the code, it's able to compile it and allow any of the above devices to run it!

This process described above is known as an Integrated Development Environment, or IDE. Xcode then is the IDE provided by Apple that allows us to create apps.

![Xcode](http://i.imgur.com/H5IUNEe.png)

Here is me opening up Xcode and starting a new project. I have the ability to begin an iOS, watchOS, tvOS or MacOS (here it's still OS X) application. It's that simple.

We can hit next and create our project. We will be asked to provide the name of our app.

![example](http://i.imgur.com/MHcgw8r.png)

After hitting next, we can begin to write our code! The language I'm using here will be Swift.

![locate](http://i.imgur.com/WGqFvDu.png)

I've selected the `ViewController.swift` file in the left pane. By doing this, this brings up a document in the center (main) window where we can now write some code!

Here's an example of me writing some code in this `ViewController.swift` file.

![ex](http://i.imgur.com/WvSiOB0.png)

So now that I've written some code in this `ViewController.swift` file, how can we make it *run*. 

In the upper left corner of Xcode, you should see what appears to be a Play Button with a Square (stop) button to the right of it. If you were to click the Play button, your app will run! So lets do that.

![runn](http://i.imgur.com/y8Mp5FA.png)

'Hello everyone' was printed to the console here. But that's not really a fun application (I know).

You should have also noticed, that something else appeared on screen when you ran your app.

![simulator](http://i.imgur.com/7JxaDCZ.png)

This is the Simulator. It simulates what your app will look like. That way, you aren't required to plug and run your app on your iPhone when developing an app. We can do so right from our computer. 

Lets change the background color to blue.

![blue](http://i.imgur.com/hzDDoMG.png)

After including this code, if we were to run our app - the simulator should look like this:

![bluee](http://i.imgur.com/zjyrEaw.png)

This is the process of creating an app.
 

It's our belief that programming Objective-C in Xcode is most effectively learned through practice. The lessons that you'll be going through will generally alternate between readings and labs. Labs are actual Xcode projects that we've set up for you so that you can get right to composing code. As the course progresses, you'll learn more and more about Xcode and eventually become capable of completing a project that you started from scratch.

**Note:** *The first time you open Xcode, your machine will ask you if you want to enable "Developer Mode". Go ahead and do this; don't be scared of it! What it does is allow you to debug your projects without OS X asking for your administrator password every time. If you previously selected "No" the first time that you opened Xcode, don't worry! Just open your terminal and type* `$ DevToolsSecurity -enable`.

## Xcode Areas

In addition to the typically-placed application Toolbar, Xcode has four main workspace windows. These are, in clockwise rotation from the left:

1. The Navigator area,
2. The Editor area,
3. The Utilities area, and
4. The Debug area.

**Note:** *If this is your first time using Xcode and you would like a sample project to explore, go ahead and fork, clone, and open the lab in the next lesson titled* "Your-First-NSLog".

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_areas.png)
—*The areas of Xcode.*

#### Configuration Buttons (Show or Hide Areas)

The three configuration buttons (![][nav_left], ![][nav_middle], ![][nav_right]) on the toolbar in the upper right corner show or hide the Navigator area, the Utilities area, and the Debug area. Additionally, the two configuration buttons inside the Debug area in its lower right corner show or hide its viewers: the Variable Viewer and the Console Output Viewer.

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_config_buttons.png)  
—*Xcode's five configuration buttons and the areas that they govern.*

#### Finding The Console Output Viewer (The Debug Console)

When your project runs, any `NSLog()`s that are executed print their outputs to the Console Output Viewer, which is often referred to as the "debug console."

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_nslog_console.png)  
—`NSLog()`*s will print to the debug console.*


#### Essential Buttons

Within the Navigator area, the first icon (![][nav_project]) displays the Project Navigator which allows you to select which file will display in the Code Editor.

The Run (`▶︎`) and Stop (`◼︎`) buttons will start or stop your application in the iOS Simulator. You can also use the shortcut keys: 

  * Run (`▶︎`): `⌘` `R`
  * Stop (`◼︎`): `⌘` `.`

The Quick Help: Reference link can be found in the Utilities area and loads itself with information about an Apple-library item when the Code Editor's cursor is placed within its text. Clicking on the "Class Reference" link will open a window showing Apple's documentation regarding the selected library item. 

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_basic_buttons.png)
—*The most essential buttons: Run, Stop, the Project Navigator pan, and the Quick Help Reference link.*

## The iOS Simulator

You'll notice that the iOS Simulator pops up as the front application window whenever you run your project. Don't be alarmed! Since all of the labs that we've set up for you to complete are iOS projects, Xcode must run them through the iOS Simulator: the program that uses your local machine that runs a version of OS X to emulate a mobile device that runs a version of iOS.

You won't actually be interacting with the iOS Simulator directly until much later in this course when we begin working with views; so for now just give it a friendly wave whenever it loads and let it run its merry self in the background.

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_ios_simulator.png)
—*The iOS Simulator loads every time that you run an application, but just let it do its thing for now.*

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/r2d2.gif)

That's just enough Xcode to start writing some Objective-C!


[nav_left]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_left.png
[nav_middle]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_middle.png
[nav_right]: https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_right.png

[nav_project]: http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_project_navigator_table.png


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/reading-ios-intro-to-xcode' title='Xcode: Just Enough'>Xcode: Just Enough</a> on Learn.co and start learning to code for free.</p>

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/reading-ios-intro-to-xcode'> Xcode: Just Enough</a> on Learn.co and start learning to code for free.</p>
