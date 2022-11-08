# Assignment7



SCSS features used:



This website is a travel agency website. The first page was styled as the landing page and the second page is all the different packages of  the agency offers. 


CSS grid was used to display the images and the corresponding text in the second packages page.


1. Varibales

The color scheme of the entire website is based on 5 colors which have stored as varibales in the _config.scss file. The different font families used are also stored as variables in the _config.css file.

2. Custom Properties 

The background color for form input was made into a custom property and stored in _config.scss file, although its only used once, to maintain uniformity any other input text box will have same color.


3. Nesting 

Used nesting to style font in one selector instead of two selectors for font-family and font-weight in the main page, used it as 
font:
  {
      family: Arial, Helvetica, sans-serif;
      weight: light;
  }


4. Interpolation 

Since there was a lot border styling , in the config.css file, defined border as $b and used interpolation selector {#b} instead of border in styles.css file 

5. Placeholder selector 

To make the code compact and to use the same code to  style a toggle button, the transition styling was stored in %toggle-switch and used in the styling of the mode change button in the second packages page. The functions are all stored in the _functions.scss page , as is this. 


6. Mixin 

As the styling of navbar has to be uniform thorughout the website, defined a mixin called navbars which has all the styling of navbar. In the two pages, in the nav section this mixin was used.


7. Functions 

 Used the built-in function transparentize($color, $number) to make the form-input box in the first page look more appealing on the backround picture. 

 