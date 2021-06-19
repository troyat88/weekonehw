# HTML and CSS: Code Refactor 
## Homework Assignment #1
---

## Assignment Objectives 
---
Refactor Code for Horiseon website for accessibility by:
1. Ensuring use of semantic elements and structure on HTML and CSS for website accessibilty.
2. Improve/modify HTML and CSS where possible for website function.

In order to complete these objectives I inspected the website for issues and implemented changes in code as needed. 
I then inspected HTMl and CSS for semantic structure and accessibility making sure to not disrupt the funtion of the website as intended by Horiseon.
---

## Areas of improvement found with initial inspection of site
1. The title if the page is "website"
2. "Search Engine Optimization" link in Nav section not working
3. No Favicon
4. Conttrast in H1 for "SEO" more confusing than obviously highlighting "SEO" for effect

## Changes made in HTML or CSS
1. Changed title element to display "Horieseon Marketing Solution" to satisfy identifying website and search engine performance.
2. HTML for the "Search Engine Optimization link was correct, however ID was missing in corresponding section within the body.
3. Added favicon using "cost-management.png" from existing Images directory
4. Switched the colors for "SEO" in Horiseon H1 element, so that rest of text is grey and SEO stands out in white

---

## Areas of improvement found in HTML (focus on semantics and accessibility)
1. Div's weere assigned ID or Class that represented parent and child semantic elements, causing HTML to be more cluttered than necessary.
2. Images were missing ALT attributes. 
3. Header section missing META content- Description. 

## Changes made to HTML
1. replaced parent DIV's Class="header","hero", "content", and "benefits" with semantic elements "header", "main-image","main", and "aside".
Also changed/condensed child DIV's Class="search-engine-optimization,"online-reputation-management", "social-media-marketing", "benefit-lead", "benefit-brand" and "benefit-cost"
to class="main-content" and "aside content". 
2. Added ALT attributes to all images, including key-words for SEO performance. Created a title attribute for "main-image" in HTML since it was added and styled as a background-image in CSS.
3. Added meta description via "head" section. 

---

## Areas of improvement found in CSS
1. CSS did not follow structure of HTML.
2. CSS sheet was cluttered by repeating styling rules.

## Changes made to CSS
1. Restructured CSS style sheet so that styling flowed with the order of elements in CSS.
2. Decluttered by using one class where multiple classes were created to style child elements of "main" and "aside" parent elements. Reflected changes made in HTML.
3. Added comments in CSS to mark what sections were being styled. 
---
 ## Link to deployed site
 https://troyat88.github.io/weekonehw/
 ---
 ## Final Product
![Rendition of Final Solution](/assets/images/HORISEON.png) 

