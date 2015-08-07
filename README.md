# Xcode: Just Enough

## Objectives

1. Get acquainted with Xcode just enough to start playing with Objective-C.
2. Distinguish the four main areas of Xcode and how to find information printed to Console Output Viewer.
3. Say hello to the iOS Simulator.

## What is Xcode?

Xcode is the **Integrated Development Environment** (**IDE**) provided by Apple to third-party programmers such as yourself for developing iOS and OS X applications written in Objective-C and Swift. An IDE is a program (or program suite) that incorporates tools for the various aspects of creating software. 

To most beginners, Xcode feels very overwhelming. It's totally natural if you share this experience. Xcode provides a deluge of functionality that's continually being expanded and improved. Learning to use the multitude of tools available through Xcode is an entire set of skills in itself. Acclimating to the Xcode environment is a significant portion of this course which aims to give you, the student, a hands-on working knowledge of using Xcode first-hand to develop mobile applications for iOS.

It's our belief that programming Objective-C in Xcode is most effectively learned through practice. The lessons that you'll be going through will generally alternate between readings and labs. Labs are actual Xcode projects that we've set up for you so that you can get right to composing code. As the course progresses, you'll learn more and more about Xcode and eventual become capable of completing a project that you started from scratch.

**Note:** *The first time you open Xcode, your machine will ask you if you want to enable "Developer Mode". Go ahead and do this; don't be scared of it! What it does is allow you to debug your projects without OS X asking for your administrator password every time. If you previously selected "No" the first time that you opened Xcode, don't worry! Just open your terminal and type* `$ DevToolsSecurity -enable`.

## Xcode Areas

In addition to the typically-placed application Toolbar, Xcode has four main workspace windows. These are, in clockwise rotation from the left:

1. The Navigator area,
2. The Editor area,
3. The Utilities area, and
4. The Debug area.

**Note:** *If this is your first time using Xcode and you would like a sample project to explore, go ahead and fork, clone, and open the lab in next the lesson titled* "Your-First-NSLog".

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

The Run (`▶︎`) and Stop (`◼︎`) buttons will start or stop your application in the iOS Simulator.

The Quick Help: Reference link can be found in the Utilities area and loads itself with information about an Apple-library item when the Code Editor's cursor is placed within its text. Clicking on the "Class Reference" link will open a window showing Apple's documentation regarding the selected library item. 

![](https://curriculum-content.s3.amazonaws.com/reading-ios-xcode/xcode_basic_buttons.png)
—*The most essential buttons.*

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

