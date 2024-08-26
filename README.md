# HTML-CSS
# What is HTML?
* HTML is the structure that contains your conent and displays it on your browser.(chrome,bing ,Microsft Edge)
  
# WHAT DOES HTML STANDS FOR?
* HyperLink Markup Language

  
# What is HTML built with?
* It is built by a block/lines of code called elements.
* They are he components that build up the HTML structure.

  
# What are elements?
* Elements are tages and attributes that makes up a syntax.

# What are Tags?
Tags are surrounded by angle brackets (< and> ) and usually come in pairs,with an opening tag and followed by the content you want to add and end with a  closing tag.

# HTML ELEMENTS
* Headings
* Nav
* Paragraphs
* Links
* Images
* Videos
* Footer
* Body
* Audio


# HTML ATTRIBUTES

# What are HTML ATTRIBUTES?
* HTML Attributes are additional information included within the opening tags of an element
* They make it easy for developers to focus on  a specific element when working with additional files like CSS by making use of their attributes.

# Types of HTML ATTRIBUTES:👩‍🏫
* 🪐Class - it makes it easier when working with CSS to specificly apply certain CSS styles to that specific element by creating a class for your element.
   In this case all elements named after the same class would then have exactly the same CSS styles.
  
* 🎀Id -it makes it easier when working with CSS to specificly apply certain CSS styles to that specific element containing a unique Id ,these changes will 
  only apply on an element with only this unique Id and no 
  other element would be affected at this point.
  In this case all elements can have their own Id's if there's any CSS changes you can then directly make changes using the Id.

* 📢lang-this attribute helps us specify which language the content is in,for example if the content of the language is n English you'd have to specify this 
   way in the code lang ="en".
![image](https://github.com/user-attachments/assets/6e99ba99-613a-4f45-aa6d-d0e14663d285)

* 📍dir -this attribute allows you to set the direction flow of your text whether to "LTR" for left-to-right or "RTL" for right-to-left

# ARIA ROLES👩‍⚖️👨‍🌾👲👨‍🎓
# WHAT ARE ARIA ROLES?
* ARIA Roles is the inclusion of users of all types including those with disabilities ,allowing accessebility to websites regardless of different devices to view the content with and also maintaining your webpage with consistent labeling of the elements and their description.

# FORMATTING HTML🛠
* When writing code on html and leave unnecessary spacing between your code ,HTML automaticaly ignores the blank spacing and displayes the content based on how the elements are structured on the code.
* HTML is not case-sensitive but it is advised to keep good practice of using lowercase when writing code.
* To make your code easier to understand for yourself and other developers it is advised to leave comments in between your line of code explaining the 
  purpose of each line or set of code
* This is how you write comments on HTML ,opening tag "<!--" at the start and "-->"closing tag at the end
* HTML has tags that automatically closes themselves with their closing tags ,those that do not have closing tags to this day where tags created in the early years of Tech.

# HTML NAVIGATION AND LINKS🔗📌
 * This how you create a basic link on HTML ,<a href="https://example.com">text to click</a
 * 📂HTML Navigation allows you to find path/routes to different folders according to the structure and direction of your folder,we use slashes as a symbol to access 
  folders through their paths.
 * 🚗For example if you have an image folder named IMAGES that consist of different folders/albums ,named "myself" ,"family" or "Vacation Pictures" and you wanna 
 access 
  the family folder here's the structure , IMAGES/Vacation-pictures.By places the original folder before the slash indicates where the path starts and by placing the 
  other folder after the slash it indicates that the route now should end on this folder and access it.
 * 🛣If  the folder you wanted to access is inside the second folder which is "Vacation Pictures" you will just need to add a slash after "Vacation Pictures" and then add the name of the folder you wanna access and end there,so the deeper you wanna accesss you folder the longer or more slashes you add after every indicatin of where an actual folder has been made. e.g IMAGES/Vacation-pictures/Paris

# HTML Working with Graphics and Images

# How to insert images on HTML?
* Here is a syntax  <img src="image.jpg" alt="a girl wearing a dress"  width="" height=""
* The above syntax consists of all the four attributes needed to make up the syntax that allows us to insert images.

# What are the four attritubes needed for the image syntax?
* Source attribute -allows you to insert the image by writing exactly what the image is named after to be able to access it.
* Alt attribute -it allows you to write a description of the image.
* Width attribute -it allows you to control the resizing of an image 
* Height attribute-it allows you to control the resizing of an image 

# why do we have to add the Alt attribute when we can already see the image?
 "Add an ALT attribute, which serves as a replacement for the image when it cannot be seen. For instance, people who are visually impaired may use a screen reader that reads the ALT text aloud to them."

# When to leave the Alt Attribute blank?
*When the is nothing important about the image or the image is just undescribable.

# Image Formats
* GIF
* PNG
-Transparent
-Can not be animated
* SVG
* JPG
 -Can not be transparent
 -Can not be animated
  

# Responsiveness of Images
* In the Image syntax there's a src attribute that allows you to add the image url that you wanna display,For a set of images that needs to be displayed according to different sizes like ,a Laptop Screen,Tablet screens and mobile phone screens you will need to add "set" after you have written src as in ( srcset) then the images will display according to the assigned screen.

# How to match caption with an image? 
* That can be achieved by Working with the figure and figcaption elements
* Syntax for that , <figure>add your image url here <figcaption>add your caption here</figcaption></figure>

# Working with Media :
# Working with Audio
*Audio Element has both the opening tag and closing tag
* The syntax is similar to the image syntax but this one is more mordern because it consists of a closing tag also.

# Working with Forms and Interactive Elements
# Forms
  # What is the form syntax?
* Firstly the form syntax consists of a form element that has an opening and a closing tag ( <Form> Name</Form> )
* Secondly there will be fields on the form ,we know the form element consists of an opening and closing tags inbetween those tags each field will be wrapped up with a label and below that there will be an input field  . Example of that would be having the first field as a name label  and below that would be the placeholder where you type in your input inside the input element.
  
* A label element also consists of an opening and a closing tag (<label></label>)
* An input element only has an opening tag (<Input name="name">

# What are forms for?

* logging into websites :
  Accessing online accounts securely with usernames and password.
* Making purchases:
  Buying products or services online through secured payement gateways.
* Conducting searches:
  Finding information online and using the search engines like Google or Bing.
* Adding content:
 creating and sharing online content like posts ,photos or videos on websites or any social media platform.

# Let's Learn CSS

# What is CSS?

* CSS is the life and color of HTML,it styles the layouts and elements of HTML and you can use it to position content and change font type and colors.
* There's a lot you can do with CSS when it comes to styling how your HTML looks.

# How is CSS structured?
* CSS is structured by rules and box model
  
# What are rules in CSS
* rules are selectors
* rules are set to be followed and done exactly how they have been set,same as how css rules apply
* rules are selectors with declaration blocks

# What are selectors?
* Selectors are used to select a specific element ,class or Id that you specifically want to style.
* Selectors have a structure called "declaration blocks" that is later set as the rule that CSS will apply on HTML according to the selector's rule.
* Selectors contain properties and properties are assigned to values.

  
  

