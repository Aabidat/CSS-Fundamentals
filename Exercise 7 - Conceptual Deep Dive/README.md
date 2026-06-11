# Conceptual Deep Dive
1. No, it is not possible to build a house using CSS with no HTML because HTML represents the walls and framework, so you cannot paint a house when you don't even have  walls and structures. CSS is the decoration, HTML is the building. You cannot decorate a building that has not been built yet.

2. Since the CSS code is in a separate document, your HTML files will have a cleaner structure and are smaller in size.
You can use the same .css file for multiple pages. For example imagine you are building a website with 10 pages and you styled every heading  with clor grey, using inline CSS on every single `<h1>`, your client then ask you to change the heading to color red. You would have to open all 10 pages and change every single heading one by one, if you missed even a single page the website would not be uniform, With external CSS, you change one line in one file and every heading on all 10 pages updates instantly.

3. Even though both rules targets the same paragraph, the paragraph will be green because you gave it a class selector in the HTML file and targeted that class in the external css. This is because the class selector is more specific than the plain selector.

4. ### Hex
       is short and fast to type, easy to copy and paste
   ### RGB 
        it is useful when you need to control colors mathematically or add transparency using rgba
   ### HSL 
       this is the easiest method to adjust by eye, you can modify just the lightness or saturation without changing the whole value
   ### Named colors 
       this is  fastest way to test out colors when you just need a quick option without looking up a code.
