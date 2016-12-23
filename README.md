# Exploring Polymer

## Project Description ##
This is a project to explore the basics of Web Components. The project is a rebuilt of a part of the front-end from the Liky application. I tried to build the front-end in as many components as possible so that they could possibly reused in future elsewhere in the application.

## Polymer basics  ##
To build the app, I made use of the Responsive app layout that Polymer offers. This layout matches the layout of the existing front-end of Liky and it was also a good first step to understand the basics of Polymer. 

## Bootstrap & jQuery ##
In the current application of Liky there is extensive use of Bootstrap and jQuery. Because of the time I also used them during this project, but I’m aware that Polymer itself can achieve the same goals. This could be a next step in exploring Web Components. 
## Structure ##

### Base ###
For this project I used the structure of the example descripted in the [Polymer Documentation](https://www.polymer-project.org).

### Pages ###
For each page the is a basic file in the root map. This file contains a basics HTML 5 structure. The references to load the external files (CSS/JS) are also placed in this file. There also is a map “pages”. Per page I created a Polymer element and referenced to it in the basic file of a page. So actually the Polymer page elements contain the <body> of the basic pages. 

### Elements ###
Each Polymer page element contains multiple elements. For the construction of the layout I used the [default Polymer elements](https://elements.polymer-project.org/elements/app-layout). These elements can be found in the “bower_components” folder. Beside the default Polymer elements, I build some custom elements. These elements can be found in the “elements” folder.  Some custom elements also contain other custom elements to keep it as dynamic as possible. 

### Element properties ###
Most of the custom element that I have built make use of properties. To make clear which properties there are for an element, I descripted the properties at the top of the code. A good example of an element that contains multiple properties is: statistic-box.html

## My opinion ##
When I first came into contact with Web Components I was very curious. I was told that this will be the new standard in a few years. After doing this project, I started to see the value of Web Components. The easiness of exchanging elements to multiple application opened a whole new world for me. I’ve become a fan! 

#### Sources ####
[Polymer Documentation](https://www.polymer-project.org)https://www.polymer-project.org/)
[Custom Elements](https://customelements.io/)

#### Polymer Packages ####
[Custom Elements](https://elements.polymer-project.org/elements/app-layout)


