# Trainer :  Raj Prudhvi ( Oracle Certified )
# HTML- The Head Element

* The HTML head element is a container for the following elements: title, style, meta, link, script, and base.
* The head element is a container for metadata (data about data) and is placed between the html
tag and the body tag
* HTML metadata is data about the HTML document. Metadata is not displayed.
* Metadata typically define the document title, character set, styles, scripts, and other meta information.

# The HTML title Element
* The title element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.
* The title element is required in HTML documents!
* The contents of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search results.

* The "title" element:
    * defines a title in the browser toolbar
    * provides a title for the page when it is added to favorites
    * displays a title for the page in search engine-results

* So, try to make the title as accurate and meaningful as possible!

# The HTML "style" Element
* The "style" element is used to define style information for a single HTML page

# The HTML "link" Element
* The "link" element defines the relationship between the current document and an external resource.
* The "link" tag is most often used to link to external style sheets

# The HTML "meta" Element
* The meta element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

* The metadata will not be displayed on the page, but are used by browsers (how to display content or reload page), by search engines (keywords), and other web services.


        * Define the character set used:
        <meta charset="UTF-8">

        * Define keywords for search engines:
        <meta name="keywords" content="HTML, CSS, JavaScript , Jquery">

        * Define a description of your web page:
        <meta name="description" content="Concepts On Html Elements">

        * Define the author of a page:
        <meta name="author" content="Raj Prudhvi">

        * Refresh document every 30 seconds:
        <meta http-equiv="refresh" content="30">

        * Setting the viewport to make your website look good on all devices:
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

# Setting The Viewport
* The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.

* You should include the following <meta> element in all your web pages:

        <meta name="viewport" content="width=device-width, initial-scale=1.0">

* This gives the browser instructions on how to control the page's dimensions and scaling.

* The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

* The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

# The HTML "script" Element
* The "script" element is used to define client-side JavaScripts.

# The HTML "base" Element
* The "base" element specifies the base URL and/or target for all relative URLs in a page.
* The "base" tag must have either an href or a target attribute present, or both.
* There can only be one single "base" element in a document!

