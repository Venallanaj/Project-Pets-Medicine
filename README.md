# Project-Pets-Medicine
Project-Pets-Medicine created with Html, Bootstrap, Css, Javascript.
I have used bootstrap gridsystem to created responsive layouts.
# Firstly explain Navigation Bars:
I have used to  navigation bar  which is a navigation header that is placed at the top of the page:
With Bootstrap, a navigation bar can extend or collapse, depending on the screen size.

A standard navigation bar is created  with nav class="navbar navbar-default" after created a class .container or 
.container-fluid by default inside put two classes firstly created a class for .navbar-header inside this class i ahvecreated another class .navbar-brand inside this div placed  logo of company or text. Secondly another class we called .navbar-nav this class we should add  unordered list  lik this ul class="nav navbar-nav" /ul inside  ul put all list item li for to create menu.

# Secondly explain Slider:
In bootstrap Slider is component of Javascrpt
The "Wrapper for slides" part:
Wrapp all images  and created a class .carousel inside a class carousel created another class .carousel-inner is party of carousel  placed all images inside class .carousel-inner.
For each images  a have created a div with class .item.

To get navigation in carousel is important to set an id (in my  case id="myslide" but you can  give what name you want ) add your id in .class  like this  div class="carousel slide" id="myslide" 

# The "Left and right controls" part:

This code adds "left" and "right" buttons that allows the user to go back and forth between the slides manually.
The data-slide attribute accepts the keywords "prev" or "next", which alters the slide position relative to its current position.
 I have add an tag a.href placed your id, class, role, data-slide 
  a href="#myslide" class="left carousel-control" data-slide="prev" role="button"
span class="glyphicon glyphicon-chevron-left" /span
 /a
 I have created another button is the same way but i have changed class with right carousel-control and so on...

 # The "Indicators" part:
 For to navigate  directly to photo is necessary  to create indicators.
The indicators are the little dots at the bottom of each slide (which indicates how many slides there are in the carousel, and which slide the user is currently viewing).

At the top of the code after class
div id="myslide" class="carousel slide" data-ride="carousel"
The indicators are specified in an ordered list with class .carousel-indicators.
The data-target attribute points to the id of the carousel.

The data-slide-to attribute specifies which slide to go to, when clicking on the specific dot.

# Our Mission
just I a have created a class .content container used to class.jumbotron for create more large text and take backgrounde grey it looks more nice,  follow by row and title and  class with .col-sm-12 placed inside
text  with p html tag.

# Our Services
I have created a class .row another class .col-sm-4 which i have placed inside a image with class .thumbnail
also I have created another class .caption   for more space and looks more better which conatain html tag h3,p, and button with  class .btn-info and so on......
   


