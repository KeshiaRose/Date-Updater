![This repo is deprecated!!!](https://img.shields.io/badge/Status-Deprecated-red)
>**The version found in this repository is out of date. Please go to the [Extension Gallery](https://extensiongallery.tableau.com/products/28) to get the latest version.**

# Date Updater
A Tableau extension that automatically updates a parameter to the current date

# Installing the Extension

Download and install the Extensions API version of Tableau Desktop from the [Tableau Extensions API Developer Preview](https://prerelease.tableau.com) site. Under **Resources**, click **Extensions API Software Downloads**. 

Current version: 18.0411.1540

Download the Date Updater [manifest file](https://keshiarose.github.io/Date-Updater/Date-Updater.trex). 

# Using the Extension
1.	Create an open input (All) date parameter.
2.	Drag in a new Extension object to your dashboard
3.	Find the manifest (.trex) file you downloaded above
4.	Select the parameter you created above for the extension to manipulate
5.  Click "Select Parameter"
6.  Your date parameter will now update to today's dat wheneve rhte extension is initialized.

Note: During authoring there are many actions that will cause the extension to reload. This is best used on server where the reload will happen once upon loading the dashboard.
