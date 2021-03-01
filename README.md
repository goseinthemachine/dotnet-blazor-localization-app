# Basic Example of Localization in Blazor application

Application currently allows for selection between english and spanish and has translations for `Hello World`

Language translations are stored in the Resources folder. The convention is to name and model the resource files and folders according to where they will be displayed.

There is a MVC API endpoint that reloads the page so that the translation takes effect.

All the localization settings are in `Startup.cs`