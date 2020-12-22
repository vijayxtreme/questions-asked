# HTML & CSS

- What new features come with HTML5?
- data-attributes, header, footer groups, audio, video tags, localStorage, article
- What are the new tags that come with HTML5? (e.g. nav, article)
- What is localStorage, how does that vary from the previous method of storage before?
- Is the iframe in HTML5?  What are the main differences?
- What is the difference between progressive enhancement and graceful degradation?
  - http://www.sitepoint.com/progressive-enhancement-graceful-degradation-basics/ 
  - checking a user’s browser to see if they support features, if they do build up, if not give the lowest possible best experience (graceful degradation) for that browser (e.g. IE has the lowest browser ability).  Progressive enhancement are features that get added to a browser with higher level ability
- Have you made any responsive design websites? Can you show us something? 
- What is the hype about Boilerplate?
- Quickly sets up a website with all the correct HTML5 to get started
- Can you code a site in straight CSS (no Photoshop layers) or slicing?
- Difference between classes and IDs?
- classes are reused again and again, ids correspond to one part of a page
- Give examples of how you would use a class vs an id
  - http://css-tricks.com/multiple-class-id-selectors/
- What is chaining in CSS? Can you show an example? 
- What is selection in CSS?
- Order of importance in CSS?
- Important tag, inline style, id, class, selector
- What are floats and how do you define one?
- What about all the contents in a div, do they stay inside a div or does just the div get floated
- How do you clear a float (or prevent more divs from coming up)?
  - `clear: both;`  or `clear: left`;
- Difference between an absolute and a relative positioned div? Does an absolute div get positioned on the page or the element (is that always the case)?
- How does inheritance work in CSS? Can you show an example
- Difference between inheritance and specificity? 
- How does Cascading work in CSS?
- New features in CSS3?
- Difference between margins and padding (aka box model)?
- What are child selectors and how do you use them? ul li vs ul > li; first targets all lis anywhere, the second only targets children directly of the ul
- What is grouping?
  - Adding extra ids or classes together to have same properties
- What is contextual selection?
  - Applying styles to tags p { } p i {} p i strong { } 
- What are four different ways to apply styles to a web page?
  - inline, embedded style tags, linked sheets, @import
- (Interviewer shows you different styles of writing CSS, can you tell what’s right / wrong)?
- How would you use Retina size images in Media Queries to show up for smaller screens?
- What are some responsive frameworks you use-- what do you do if the theme doesn’t work with Bootstrap or some other framework?
- What are boxes in CSS?
  - the wrapping around an html element -- padding, margin, border, content
- Why do we need it? (What would happen without the box model?)
  - What is the difference between div.reward and div .reward?
  - div.reward  /* matches every div with class="reward" */
  - div .reward /* matches any descendant (child, grandchild...) of any div if the descendant has class="reward" */
  - Basically if a class is written without a element in front of it, it goes to the root * and pretty much envelopes all of the html tags with class ‘reward’.   If you wrote .class h1, it would look for all classes of h1 on the root
- What are the advantages of using a CDN versus a local distribution?
  
## SASS / LESS / Preprocessors

- What are the advantages and disadvantages of using SASS/LESS?  How do they work?
- Mixins, Variables, Nesting, Partials, Inheritance / Extending, Operations
- Have you worked with SASS/LESS?
- Are there any web implementations you use, or do you just use SASS lightly? E.g. frameworks? (Compass, Bourbon)
-  Why would someone want to use SASS anyway?
- LESS can be loaded in browser, which could complicate stuff

## Bootstrap

- What work have you done with bootstrap?
- What is Bootstrap and how does it help with web design?
- Do you prefer Bootstrap or JQuery?  Which one would you use if you could only pick one?
- What are the major differences between Bootstrap 2 and Bootstrap 3? 4?
- What are some ways responsive design gets handled with Bootstrap -- how is it different via mobile, tablet, and desktop?


## CSS Frameworks

- Have you used other CSS Frameworks (Semantic UI/Bulma.io)
- Are you familiar with CSS with React?