Quick Check Q1:  You change the footer colour in styles.css. How many pages update? What if the same 
colour was only set with an inline style on index.html? 
Ans: •  All 5 pages update when changed in styles.css. 
 If set with an inline style on index.html, only 1 page (index.html) updates. 

Quick Check Q2:  Which is more specific: h1 or #welcome? If both set color, which wins? Write a one-line 
proof from your page.  
Ans:  Which is more specific: #welcome.
  Which wins: #welcome wins because ID selectors beat element selectors.
  One-line proof: <h1 id="welcome"> turns red when styled with both h1 { color: blue; } and #welcome { color: red; }.

Quick Check Q3:  Convert #0369a1 into an approximate rgb(...) value (you may use a colour picker). Why 
do designers often prefer hex in stylesheets?  
Ans: RGB conversion: #0369a1 equals rgb(3, 105, 161).
Why designers prefer hex: Hex codes are shorter, easier to copy-paste, and more compact to read in stylesheets.

Quick Check Q4:  Set a nav link to display: none, then to visibility: hidden. What is the difference in the 
layout?   
Ans: display: none removes the element completely from the document flow, leaving no gap.
visibility: hidden hides the element but keeps its space in the layout, leaving an empty gap.

Quick Check Q5:  In your wireframe, how many event cards appear side-by-side at phone width? At 
desktop width?   
Ans: Phone width: 1 card (stacked vertically).
Desktop width: 3 cards (or 4, depending on your Bootstrap grid layout).

Quick Check Q6:  Why must styles.css be linked AFTER the Bootstrap CSS file? What happens if you reverse 
the order and both set h1 colour?  
Ans: styles.css must be linked AFTER the Bootstrap CSS file so that your custom styles can successfully override Bootstrap's default rules.
In CSS, when two styles have the same specificity (like targeting h1), the browser follows the cascade rule and applies whichever rule appears last in the HTML document.

