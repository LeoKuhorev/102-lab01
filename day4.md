## Day 04 "HTML, CSS and JS" 

**Structure web pages with HTML**

`<!DOCTYPE html> <!--shows what type of html your page uses-->`  
`    <html>`  
`        <head> <!--whatever is in this tag will not be visible on the page-->`  
`            <title> <!--name of the browser tab-->`  
` `  
`            </title>`  
`        </head> `  
`        <body> <!--whatever is here - will be on your page-->`  
`        </body>`  
`    </html>`  


More tags:  
`<header> </header>`, `<footer> </footer>` - these tags can be used for :
    - main header/footer that appear on every page;
    - header/footer of an individual page;  
`<nav> </nav>` - element is used to contain the major navigational blocks on the site (primary navigation). Can be used for links that appear on every page;  
`<article> </article>` - for content, can be nested;  
`<aside> </aside>` - can be used in 2 ways:
    - when it's inside `<article>` it should contain information not directly related to the article (glossary etc);
    - when it;s not inside `<article>` - should contain content related to the entire page (links etc);  
`<section> </section>` - groups related content together. Typically contains it's own heading.   
    `*`Do not group the entire page with `<setion>` - use `<div>` instead;  
`<hgroup></hgroup>` - groups `<h1>..<h6>` tags together (for example, when you have heading and subheading);  
`<figure></figure>` - for images, videos etc. Should contain `<figcaption></figcaption>` tag with image description;  
`<div>` - use to group content when other more specific tags don't apply;  
`<h1>...<h6>, <p>, <ul>, <li>` - are block elements (will start from a new line);  
`<a>, <b>, <em>, <img>` - inline elements (will stay in the same line);  
`<span></span>` - inline equivalent of `<div>`;  
`<iframe></iframe>` - inserts other window into your page.  

**Design web pages with CSS**

`<link href = "style.css" type = "text/css" rel = "stylesheet">` - goes into `<head>` with link to your CSS file.


**Activate web pages with JavaScript**

JavaScript is case sensitive!  
`document.write('Good Afternoon!');` will print "Good Afternoon!" whenever this line is inserted:  
`<script src="js/add-content.js"></script>`

Main features:
- flow control (how we make decisions);
- variables;
- data types;
- functions.

[Go back to page 1](readme.md)