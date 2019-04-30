# Setup Commands

Currently there are 5 AddIn files. Each can be accessed/used in Revit 2018 by navigating to the AddIns tab, then clicking external tools on the far left of the screen. External tools will have a drop-down list of each AddIn command. Each AddIn functionality is described as below.

HelloWorld.ADDIN - This will simply bring up a dialog box with any information we want, in this case Hello World!

CopyPasteGroup.ADDIN - This will allow for you to copy and paste furniture from one place to another. To do This you must click the add in from the external tools drop down, then select the Group of furniture you wish to copy. Once selected, you can then select a new area for the group to be copied into. The furniture must be a GROUP and not an individual family instance.

RetrieveSelectedElements.ADDIN - Select any number of elements in Revit then select this AddIn from the external tools drop down. This will return each element ID.

RetrieveFilteredElements.ADDIN - Select any number of elements in Revit then select this AddIn from the external tools drop down. This will return how many selected elements, then will filter only to walls, and return the selected walls.

T_GetElementInfo.ADDIN - Allows for the user to click an element and the information over clicked element is returned. Can be modified easily to return specified info.
