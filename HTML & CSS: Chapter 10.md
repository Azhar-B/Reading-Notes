# Chapter Ten

## Introducing CSS

### What is CSS?

CSS stands for Cascading Style-Sheet. It is helps a programmer design and style their html code. CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

1. Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
    * There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
        * Universal Selector: Applies to all elements in the document
        * Type Selector: Matches element names
        * Class Selector: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol
        * ID Selector: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol
        * Child Selector: Matches an element that is a direct child of another
        * Descendant Selector: Matches an element that is a descendent of another specified element (not just a direct child of that element)
        * Adjacent Sibling Selector: Matches an element that is the next sibling of another
        * General Sibling Selector: Matches an element that is a sibling of another, although it does not have to be the directly preceding element


2. Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

3. Rules of Importance: 
    * LAST RULE: If the two selectors are identical, the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.
    * SPECIFICITY: If one selector is more specific than the others, the more specific rule will take precedence over more general ones.

CSS declarations that sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon. Ex: h1, h2, h3 {font-family: Arial; color: yellow;}.

1. Properties indicate the aspects of the element you want to change. For example, color, font, width, height and border.
2. Values specify the settings you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be.

### Types of CSS

#### External CSS

External CSS uses a separate page for the styling of a website. External CSS is useful as you can use one sheet for a whole website and if you need to make changes, you can just change that one style sheet. It also helps with clarity and structure of both the HTML and CSS. 

1. The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:
    * href: This specifies the path to the CSS file (which is often placed in a folder called css or styles).
    * type: This attribute specifies the type of document being linked to. The value should be text/css.
    * rel:  This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

#### Internal CSS

Internal CSS uses the page itself. Internal CSS is important if you want to specific work on on page only.

1. You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/css. When building a site with more than one page, you should use an external CSS style sheet. This: 
    * Allows all pages to use the same style rules (rather than repeating them in each page).
    * Keeps the content separate from how the page looks.
    * Means you can change the styles used across all pages by altering just one file (rather than each individual page).

