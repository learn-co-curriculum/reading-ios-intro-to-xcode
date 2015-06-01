#Intro to Xcode
------

##Xcode Anatomy
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_overview.png" width=100%>

##The Navigator Area
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_navigator.png" >

|icon|navigator menu item| description|
|-----------|:--------------------|:----------:|
|![](http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_project_navigator_table.png)| Project navigator |Add, delete, group, and otherwise manage files in your project, or choose a file to view or edit its contents in the editor area.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_symbol_navigator_table.png" >| Symbol navigator |Browse the symbols in your project as a list or hierarchy. Buttons on the left of the filter bar let you limit the shown symbols to a combination of only classes and protocols, only symbols in your project, or only containers.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_find_navigator_table.png" >| Find navigator|Use search options and filters to quickly find any string within your project.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_issue_navigator_table.png" >| Issue navigator|View issues such as diagnostics, warnings, and errors found when opening, analyzing, and building your project.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_test_navigator_table.png" >| Test navigator|Create, manage, run, and review unit tests.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_navigator_table.png" >| Debug navigator|Examine the running threads and associated stack information at a specified point or time during program execution.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_breakpoint_navigator_table.png" >| Breakpoint navigator|Fine-tune breakpoints by specifying characteristics such as triggering conditions.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_report_navigator_table.png" >| Report navigator| View the history of your build, run, debug, continuous integration, and source control tasks.|

##Workspace Toolbar
<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_toolbar.png" width=100%>

|icon|workspace configuration button|description|
|--------|--------|:-------------:|
|![](http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_left.png) | Show and hide the **navigator area**| Use this area for navigating all facets of your project, including files, symbols, breakpoints, build issues, tests, breakpoints, and build reports. You can also search for any string in your project.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_middle.png" >| Show and hide the **debug area**| Use this area for viewing variables, interacting with the debugger console, and controlling the execution of your application.|
|<img src="http://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_workspace_nav_right.png" >| Show and hide the **utilities area**| Use this area to inspect or modify attributes of files, graphical user interface elements, sprites, and other elements in your project. Also use it to access a library of ready-made resources.|

##Run Your App
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_run_menu_overview.png" width=100%>

###Choosing a Destination
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_run_destination.png" width=100%>

- Command-R is the shortcut to run the app.
- You can run your app on the iOS simulator by selecting any of the available simulators in the destination menu.
- To run your app on your iOS device, you can select `iOS device` from the destination drop down menu. This requires a valid Apple developer account. 

**Note-** the iOS Device option can automatically become selected when an iOS device is plugged into your computer.

##Debug Your App
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_overview.png" width=100%>

###Breakpoint Gutter
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_breakpoint_gutter.png" width=100%>

###Debug Area- Control Execution and View State Information
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_area_detail.png" width=100%>

|icon|program execution control symbol|description|
|---------|-------------|:--------------:|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_pause.png" >| Pause| Pause button suspends execution of the app.|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_play.png" >| Play| Play button continues execution of the app.|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_step_over.png" >| Step Over| Step over will execute the current line of code, including any methods.|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_step_over.png" >| Step Over| Step over will execute the current line of code, including any methods.|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_step_into.png" >| Step Into| If the current line of code calls a method, step into starts execution at the current line, and then stops when it reaches the first line of the a called method.|
|<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_debug_step_out.png" >| Step Out| Step out executes the rest of the current method or function.|

##Test Your App
<img src="https://ironboard-curriculum-content.s3.amazonaws.com/iOS/intro-to-xcode/xcode_test_overview.png" width="100%">

- Command-U is the shortcut to test the app.
