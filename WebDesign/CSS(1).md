##Getting IE8 to Understand HTML5
```html
<!--[if lt IE 9]
<script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
```
### HTML to Forget
* Ditch <font> for controlling the display of text
* Don't use the <b> and <i> tags to emphasize text. Using the `<strong>` tag and `<em>`tag.
* Skip the `<table>` for page layout.
* Don't abuse the `<br>`tag.
* As a general rule, adding attributes to tags that set colors, borders, background images, or alignment-including attributes that let you format a table's colors, background, and borders-is pure old-school HTML.
* [W3C's Validator](http://validator.w3.org)

## External CSS
```html
<link rel="stylesheet" href="css/styles.css">
```

### Class selector
* All class selector names must begin with a period. That's how web browsers spot a class selector in the stylesheet
* CSS permit only letters, numbers, hyphens, and underscores in class names
* After the period, the name must always start with a letters
* Class names are case-sensitive

### Divs and Spans
* The `<div>` tag identifies a logical division of the page, like a banner, navigation bar, sidebar.


* `p.intro` means that the intro class must be applied specifically to a <p> tag(<p class="intro">) for this style to work.

* An `em` is the default browser font-size, so `2em` is twice the normal text size.

### Inheritance
* Inheritance is the process by which some CSS properties applied to one tag are passed on to nested tags.

#### Inheritance doesn't strictly apple:
* As a general rule, properties that affect the placement of elements on the page or the margins, background colors, and borders of elements aren't inherited.
* Web browsers use their own inherent styles to format various tags ***It's usually a good idea to eliminate these build-in browser styles-it'll make designing sites that work consistently among different browsers easier.***
* When styles conflict, the more specific style wins out.
* The browser uses the more specific styling
* 
