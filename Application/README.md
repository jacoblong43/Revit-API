
# Setup Applications

Currently there are 5 AddIn files. Each can be accessed/used in Revit 2018 by navigating to the AddIns tab, or a newly created tab from one of the following Addins. Each AddIn functionality is described as below.

T_App_HelloWorld.ADDIN - This will simply bring up a dialog box with any information we want, in this case Hello World, but through an application (Button) instead of a command.

AddPanel.ADDIN – This adds a panel/button to the Revit UI.

CustomTabRibbon.ADDIN – This Addin creates a new Tab and lists many different types of buttons that can be used/created.

FilterRibbonButton.ADDIN - Select any number of elements in Revit then select this AddIn from the Addins Tab as a button. This will return how many selected elements, then will filter only to walls, and return the selected walls.

DFWtags0.ADDIN – This Addin can be found under its own tab and modifies the functionality of how we tag elements. It will take into account what the user is trying to tag and understand if said element is new or existing, and color code the tag accordingly. It will also snap the leader end of the tag into the middle of the duct and when wanted create a perpendicular angle for the elbow point to compliment neatness. The line connecting the leader end and the elbow point do not have to be vertical, depending on where the user selects the elbow point, said angle can be virtually anything. The landing though will always be horizontal from the leader elbow. 
