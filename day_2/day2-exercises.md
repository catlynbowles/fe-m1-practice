1. Ordered lists use numbers, unordered use bullets, definition lists define terminology.
2. <a href="http://www.imdb.com">IMDB</a> the link is the page it takes you to, the IMDB
is the text the user clicks on, the <a href="link"> is opening tab and </a> is the closing
tag.
3. use the target attribute to open a new tab when a link is clicked. Example:
<a href="http://website.com" target="_blank"> WEBSITE </a>
4. the id attribute will link you to a specific part of the same page. <h1 id="Top"> later...
<a href="=!top"> the =! is an equals sign with a cross thru it.

CSS
1. The purpose of CSS is to integrate style rules with HTML elements.
2. cascading means if there are two or more rules that apply to the same element, there is a certain
order in which they will take precedence. more specific will take rule over more general ones,
the latter of the two rules will take precedence if they are identical. add !important to indicate
that it's more important.
3. A CSS rule contains two parts: a selector and a declaration. p {
font-family: Arial;} p is the selector, font-family: Arial is the declaration. This is saying all <p>
elements should be shown in Arial. Selectors indicate which element the rule applies to. can apply to more than one
with a comma between elements. declarations indicate how the elements referred to in the selector should
be styled. declarations are split into two parts: a property and a value, seperated by a colon. declarations
sit inside curly brackets.
4.<link> is used to tell th browser where to find the CSS file used to style the page. It is an empty
elemen (does not need a closing tag) and lives inside the <head> element. <link href="css/styles.css" type="text/css"
rel="stylesheet" /> type specifies the type of doc being linked to, rel is the relationship between
the HTML page and the file it is linked to. The value should be a stylesheet when linking to a
CSS file.
internal CSS can be placed inside a <style> element the value should be text/css <style type="text/css">
5. internal vs external CSS: when building a site with one or more page, use external CSS. This allows
pages to use the same rules, keeps current content seperate from how page looks, and means
you can change the style across all pages by altering just one file, vs doing it for each individual
page.
6. a color hex code is a value provided next to a color, they are specified in values of R, G, B.
#66cdaa
7. HSL is Hue, Saturation, and Lightness
8. in typeface: serif: extra details on ends of main strokes sans-serif: straight ends to letters
monospace: fixed width they align nicely making text easier to follow.
9. pixels (px), percentages, ems 
