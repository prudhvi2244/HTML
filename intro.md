# Trainer : RAJ Prudhvi ( Oracle Certified )
# HTML [ Hyper Text Markup Language ]
* HTML is the standard markup language for Web pages.
* HTML describes the structure of a Web page
* HTML consists of a series of elements
* HTML elements tell the browser how to display the content
* HTML is not a programming language

# Anatomy of an HTML document

        <!DOCTYPE html>
        <html>
        <head>
            <meta charset="utf-8">
            <title>Index Page</title>
        </head>
        <body>
            <h1>Welcome To HTML By RAJ</h1>
        </body>
        </html>

* !DOCTYPE html - It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly.

* html - the "html" element. This element wraps all the content on the entire page and is sometimes known as the root element.

* head - the"head" element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

* meta - This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.

* title - This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.

* body - This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

# The main parts of HTML element are as follows:

        <p>Welocome TO HTML</p>

* The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
* The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
* The content: This is the content of the element, which in this case, is just text.
* The element: The opening tag, the closing tag, and the content together comprise the element.

        <p class="class1">Welocome TO HTML</p>

* Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and "class1" is the attribute value. The class attribute allows you to give the element a non-unique identifier that can be used to target it (and any other elements with the same class value) with style information and other things.

* An attribute should always have the following:

    * A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
    * The attribute name followed by an equal sign.
    * The attribute value wrapped by opening and closing quotation marks.

# Nesting elements
* You can put elements inside other elements too — this is called nesting. 
* If we wanted to state that  "Welcome To HTML By Raj Prudhvi", we could wrap the word "Raj Prudhvi" in a "strong" element, which means that the word is to be strongly emphasized

        <h1>Welcome To HTML <strong>By RAJ</strong></h1>




