ShortlistCustomCss
==================


##Custom Esri Story Map Shortlist CSS

###Use

This file will give you the ability to customize the front-end of the Esri Story Maps Shortlist Template.  If you have ever wanted to change fonts, size, or backgrounds in the template this file will help with that.  Be aware that these are common customizations that you can make, and it by no means an all inclusive customization of the template.  This is simply a template that was put together to help speed up the process of customization.

### Requirements

In order to use this template file you must have downloaded the Esri Story Map Shortlist Template, and have access to an ArcGIS Online Subscription.  Additionally, it is also required that your Shortlist Template is downloaded and functioning on your web server. If you don’t have these affairs in order than please follow the links below to get you up-and-running and then return back to repo.  

### Not familiar with CSS….but I want to learn!

Not familiar with how to use CSS?  Are you new to the web development world in general?  Well, that’s not a problem, as long as you’re willing to learn just a little to make it happen.  

####Free Coding Resources

+ {Code Academy} (http://www.codecademy.com/tracks/web)
+ {TutsPlus} (http://webdesign.tutsplus.com/tutorials/the-best-way-to-learn-css--webdesign-11906)
+ {Mozilla Developer Network} (https://developer.mozilla.org/en-US/learn/css)

####Getting an ArcGIS Online Subscription 

Developer
+ https://developers.arcgis.com/en/sign-up/

Trial or Paid
+ http://www.arcgis.com/features/free-trial.html
 
####Download Esri Story Maps Shortlist Template

http://bit.ly/19bJtvJ

####Get Started Using the Shortlist - Tutorial
http://storymaps.arcgis.com/en/app-list/shortlist/tutorial/


###Before Adding the File 

The file that you’re adding is going to be a simple custom CSS file.  For those of you that are familiar with that sort of thing this is going to be really straightforward.  You just insert the reference tag into the head and you are ready to start customizing.  For those of you that are not familiar I recommend using the coding resources that I have provided above.  

###What each files does

####custom.css 
+ This file has selectors in place, but there isn’t any CSS applied to them.  This is a blank template that you can start adding your style to.


####customMade.css
+ This file has all the same selector as in the **custom.css**, but I have already applied some styling.  This will be helpful if you want to see how changes are being applied, and also what areas you may not want to customize.


###Adding the File

You can download the file from here, and then add it to the folder ***css*** folder of the Esri Story Maps Template that you downloaded previously.



####Where to add the file

You want to add the file directly below the style.css reference in the ***index.html*** file

####custom.css

This file loads in the template selectors that you can customize at will:

````html
<link rel="stylesheet" type="text/css" href="css/custom.css">
````

####customMade.css

This file loads in the same template selectors as the ***custom.css***, but already has styling applied to them for reference.

````html
<link rel=”stylesheet” type=”text/css” href=”css/customeMade.css”>
````









