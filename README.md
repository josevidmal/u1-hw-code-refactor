# u1-hw-code-refactor
ITESM Coding Bootcamp - Unit 1 Homework - Code Refactor

This was an on-the-job ticket activity where I was given an HTML and CSS code to refactor. The ultimate goal was to modify the HTML code to include semantic HTML elements instead of the original sectioning &lt;div&gt; elements it had. Doing this also led me to structure the HTML elements in a logical way (independent of the styling). Another thing I did was modifying the id and classes. For one part there were some elements with unnecessary classes assigned, and others that were lacking an id (which was required for the &lt;nav&gt; links to work correctly). I also included alt attributes for all the &lt;img&gt; elements, to take care of the web accessibility aspect of the website. 

For the CSS code, I made the necessary modifications to the selectors, so that the changes done to the HTML (like adding semantic elements) could work with the CSS rules for the styling of the webpage. One thing I detected was that there were redundant CSS rules in the original code. What I did was to consolidate many properties for several elements, this was done using element selectors for some of the semantic HTML elements and modifying some class selectors to actually change the styling of multiple elements.

Finally I added HTML comments and CSS comments to each file, so that other developers can undestand all the modifications I did to the HTML and CSS code. 

The final website looks like this image:

![Horiseon-Digital Marketing Agency](./Develop/assets/horiseon-digital-marketing-agency.png)

The link for the deployed application is this:

https://josevidmal.github.io/u1-hw-code-refactor/