# Salad-Restaurant

This website was created for an imaginary restaurant “SaliVinos”, which specializes in a Farm Fresh Salads, appetizers and Fine wines. 

The website consists of 7 pages: Home page, Appetizers (hors devours), Salads (greens), Wines (Vino), an About page, Contact page, and an Email List signup page for special events…etc. 
I have included in this project Custom CSS classes and JavaScript. 



## Custom CSS Classes
A few of the classes I’ve created are:
1.	.mobile-menu

This class targets the top navigation menu. I have used it to apply padding, margins, color, display, hover effect, direction & alignment, as well as media query breaks that modify the direction in smaller screens. 

2.	.mobile-dropdown

Similar to the above, this class is used specifically in the media query to assist in the directional, padding, and margin changes on smaller screens. 
	
3.	.container
This class targets the main content on many of the pages, also applying positions, margin and padding. I also used it to apply a parchment style paper image behind the text to give the effect that you are reading a paper menu, but which also was given opacity to slightly view the background image of the page. 

4.	.saladlist

Used specifically on the salad menu, to effect the display, position, margin, padding, font-size and weight. 

5.	.ingred
This class targets specific ingredients listed inside the container class, allowing me modify the font-size and style of the content. 

6.	.page1 ; .page2 ; .page3 ; .page4 ; .page5 ; .page6 ; .page7
Each page has it’s own main class specified by it’s page number. I used this to apply background imagery, and main content text formats. 




## Custom JavaScript
I have added a couple of JavaScript functions to add creativity to the site. The ones used are:

1.	Var today = new Date()   &  onload= alert(today)

I’ve used this to create an alert that pops up each time the home page loads with the current date and time. 



2.	On the “Join the Vino Club” page, I have added a custom JS Submit Form that collects users:
      a.	Name
      b.	Email
      c.	Phone number
      d.	Date of birth 
      e.	Gender
Users have the option to sign up for a mailing list that would provide them with periodic news or tastings events. 



3.	$(document).ready(function(){
        $(“.mobile-menu).on(‘click’, function (){

Is used to effect the navigation menu during the media query such that the menu button can be clicked collapse into a single menu button or open for full view. Using this allows for easier reading on smaller screens, by getting the navigation menu out of the way. 



## Images (logo)

	I have included a custom logo image: SaliVino2.png  which appears on each of the pages, and can be found in the image folder

