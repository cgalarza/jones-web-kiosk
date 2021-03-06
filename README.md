Jones Web Kiosk (Jones Movie Search)
=====================================

Author
------
Created by Carla Galarza for the Jones Media Center (JMC), Dartmouth College.  
Carla.M.Galarza@dartmouth.edu

Basic Overview and Features
---------------------------
The goal of this website is to provide patrons an easier way to search for DVDs and VHSs available at the Jones Media Center online. The website's homescreen is a set of promotional movies that change based on holidays. Patrons can search by genre under the "Search by Genre" tab by clicking on one of the genres. Patrons can also search by keyword by entering a keyword in the search box. The website pulls the information from the Dartmouth Library Catalog and reformats it so that it is displayed in a more visual appealing manner.


External Library/Plugins Used
-----------------------------
**jQuery 1.11.2**  
Used to reformat each film's information.

**Owl Caurosel**  
Used display promotional films on the home screen. More information about the
plugin can be found at [here](http://www.owlgraphic.com/owlcarousel/).

**Bootstrap 3**
Used a customized version of bootstrap on the page. The json specifying
the configuration used is at libraries/bootstrap/config.json.

**Handlebars.js**
Using Handlebars template to display each movie record. Handlebars will make
up keep of movie record html easier.

**preloaders.net**  
This website was used to generate the loading GIF.


Directory Structure
-------------------
As a reference, this is the directory organization used.
```
library/ (Any external libraries/plugins used)
    bootstrap/
    jquery/
    owl-carousel/
    handlebars/
resources/ (Code specific to this site)
    css/
    data/
    images/
    js/
    php/
*.html
README.md
```

Future Features
---------------
* Automatically generate a recent acquisitions file based on this [rss feed] (http://library.dartmouth.edu/newacq/RSS/latest/type-av.xml).
* Integrate the Rotten Tomatoes and Internet Movie Database API (IMDB).
* Modify the website to make it mobile friendly.
* Further automate image identification and matching.
* Provide a way to flag mismatched images.
