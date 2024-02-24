##Read me## 
https://dalbaebb.github.io/Coursera-ForWebDevelopers/

-----Browser sync: ------
Browser sync for static: browser-sync start --server --files "*"
Browser sync for dynamic: browser-sync start --proxy "myproject.dev" --files "*"

-----Semantic elements: ------
Tell us about content they store.Are crucial for SEO.
These are h1 (only use for crucial information),h2..., article, section, header, footer, nav (navigation), aside.
Must be used to imporve the understanding of the code by engines and computers. 

-----Character Entity: ------
<,>, and & must be replaced with &lt; ,&gt;, &amp; to avoid rendering issues 
It is generally a good idea to replace all special symbols in text with these entities

-----Links: -----
Anchor tag <a></a> is both an inline element and block element.
It can be used to point to external links and internal files. (with attribute target = "_blank" it opens a link in a new tab)
It can also be used to send the user to some content in this page, when refering to the id of that content (href="#section3")

-----Images: -----
It's good to specify width and height of an image with attributes, because this way you let the browser know that specific amount of space
should be reserved for that image, even if it doesn't load