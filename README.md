For layouting HTML tags are classified into two main display types

1. Block level elements 
---------------------------
Block-level elements typically start on a new line and occupy the full width available in their parent container.

They create a "block" or a distinct section within the content.

<div>, <p>, <h1>to <h6>, <ul>, <li>, <table>, and <form> etc

usage: Block-level elements are typically used for creating the main structure and layout of a webpage. They often define sections or containers, such as headers, paragraphs, lists, and forms.

2. inline elements 

Inline elements do not start on a new line and only occupy the width necessary for their content.

They flow within the content, appearing within the same line as adjacent elements.

<span>, <a>, <strong>, <em>, <img>, and <br>

usage: Inline elements are used for styling and enhancing the content within block-level elements. They can be used for applying emphasis, creating links, or styling text within paragraphs, for example.

All HTML tags are associated with margin and padding by default by browsers

Blue color : for actual content of the html tag
orange color: for margin 
green color: for padding  

( these color options will appear upon inspecting in developer tools clicking arrow at top left corner and selecting the respective elements)

Margin is the space outside of an element's border, and it separates the element from other elements in the layout.

It controls the spacing between the element and its neighboring elements.

Padding is the space between an element's content and its border. It defines the internal spacing within the element.

Padding does not affect the space between the element and its neighboring elements; it only influences the content area's spacing.


-------------------------


HTML (Hypertext Markup Language) allows you to use various attributes within HTML elements to provide additional information or to control how elements are displayed or behave. 

id - when we want to select HTML element uniquely

class - Used to define one or more class names for an element. It is typically used for styling with CSS and can be applied to multiple elements

style: Allows inline CSS styling for an individual element.

src - to specify the source url  img, aduio, video,script, iframe

href - Specifies the URL to which a link (anchor) element points.


alt -Provides alternative text for images and other non-text content. It's essential for accessibility.

title -  Provides additional information about an element, often displayed as a tooltip when the mouse hovers over the element.

width and height -  to specify the width and height of an element
block level and inline elements  e.g. div and img


to learn about HTMl additonally please refer https://developer.mozilla.org/en-US/docs/Learn/HTML

--------------

URL-Uniform Resource Locator - address where we can get a resource from the web

Absolute URLs and Relative URLs are two methods for specifying the location of resources like web pages, images, stylesheets, and more on the internet or within a website. 

Absolute URL:
An absolute URL specifies the full web address or path to a resource, including the protocol (e.g., "http://" or "https://"), domain name, and directory structure. Absolute URLs provide the complete address for locating a resource, and they are typically used when linking to resources outside of your own website or when specifying the exact location of a resource.

Relative URL:Relative URLs are shorter and rely on the context of the current page to determine the resource's location. They are often used when linking to resources within the same website or directory.

1. Relative to the Current Directory: A relative URL that specifies the location of a resource based on the current directory (folder) of the referencing document.

e.g. images/pic.jpg

2. Relative to the Root Directory: A relative URL that specifies the location of a resource based on the website's root directory. It typically starts with a leading slash ("/").

e.g. /images/pic.jpg

3.Relative to the Parent Directory: A relative URL that specifies the location of a resource based on the parent directory of the referencing document. It typically includes "../" to navigate up the directory structure.

../images/pic.jpg
