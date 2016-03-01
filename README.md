# Mobile Layout 1
## Build out a simple mobile website using HTML and CSS
###### Due Monday, February 08, 2016  CSS and SCSS (Sassy CSS)
## Objectives
###### Learning Objectives
After completing this assignment, you should…

* be able to target and style elements with CSS
* use Digital Color Meter to determine colors of things on your screen
* understand how to use pixels to specify measurements in CSS
* know how to validate your HTML using the W3C validator sublime plugin
* understand the difference between a head tag and a header tag
## Performance Objectives
After completing this assignment, you be able to effectively use

* CSS classes
* CSS margin property
* CSS border property
* CSS background-color property
* CSS height property
* link tag
* section tag
* div tag
* header tag
* head tag
* footer tag
* pixel units of measure
* Hex colors
* W3C validator
* Digital Color Meter

## Details
###### Deliverables
* A directory containing at least:
  * index.html
  * other-page.html
  * styles/main.css

*You should zip up the directories, and submit the URL. Example of how to do this: *

1. Create a free account on Dropbox
2. Upload the zip file to dropbox
3. Click share and submit the share URL

###### Requirements
* No legitimate W3C validation errors.
* The page should be responsive, meaning that if the browser window expands, the colored blocks should expand with it. However spacing between elements should remain fixed.
* You must use Normalize.css for cross browser consistency.

## Normal Mode
Using your knowledge of HTML and CSS, replicate the mobile layout displayed in this image file in a file called `index.html` within your dist directory.

![alt text][logo]

[logo]: https://github.com/TIY-Austin-Front-End-Engineering/mobile-layout-1/raw/master/page1.png

Next, replicate the mobile layout displayed in this image file in a file called `page2.html` within your dist directory.

![alt text][logo]

[logo]: https://raw.githubusercontent.com/TIY-Austin-Front-End-Engineering/mobile-layout-1/master/page2.png

You'll notice that only the first layout has pixel dimensions labeled for you. You must determine the correct measurements for yourself for the second page. Command+Shift+4 is your friend.

Put all of your css for both pages in a `main.css` file within a css directory within your dist directory.

Your home page (`index.html`) and your second page (`page2.html`) should have links should have links to each other (see the navigation at the top of the files). Additionally, you should add one more external link to a website of your choice on either your home page or second page.

You must use [Normalize.css](http://necolas.github.io/normalize.css/) for cross browser consistency.

## Hard Mode
Hard mode is optional if you have extra time and want to challenge yourself.

Trim down your total HTML to 1650 characters or fewer _while maintaining proper indentation and understandable class names_. It's no good if your markup is unreadable.

Trim down your total CSS to 2000 characters or fewer _while maintaining proper indentation and understandable class names_. It's no good if your CSS is unreadable. Don't count CSS normalization code if you are using something like normalize.css.

*The goal here is to make your code as efficient as possible. Cut out all the unnecessary markup and styling.*

Other things to try if you have time: modify your normal mode assignment to add a bio of yourself to one of the boxes. Add a drop shadow to the text. Modify 4 other boxes to have a drop shadow. The drop shadow should disappear when you mouse over a box.

## Notes
When you submit, it should be a link to a dropbox website ([instructions](http://www.maclife.com/article/howtos/how_host_your_website_dropbox)), a link to a GitHub repository (if you already know how to do this), or a link to a github issue with the HTMLs and CSS files in it.

Hints: You will need to use either the CSS margin or padding properties to get the layout correct. What is the difference between margin and padding? I'd also recommend using normalize.css to make sure that you start with some consistent styles.

To measure the size of elements and the space between them you can use `⌘ + shift + 4` then click and drag. Normally this will take a screen shot, but it will also show the pixel dimensions of the area you are selecting. You can press `space bar` while you are in the middle of a drag to move the entire selection.

I recommend downloading the image file and viewing it in preview at 100% zoom for accurate measurements.

Make sure that after you finish your second page, your first page still looks correct. A common mistake is to have CSS rules overwrite each other.

## Additional Resources

* [CSS margin property reference](http://tympanus.net/codrops/css_reference/margin/)
* [CSS padding property reference](http://tympanus.net/codrops/css_reference/padding)
* [CSS border property reference](http://tympanus.net/codrops/css_reference/border)
* [CSS background-color property reference](http://tympanus.net/codrops/css_reference/background)
* [CSS height property reference](http://tympanus.net/codrops/css_reference/height)
* [CSS class selector reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
* [HTML link tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)
* [HTML section tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)
* [HTML head tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)
* [HTML header tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
* [HTML div tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
* [HTML footer tag reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)
* [Normalize.css](http://necolas.github.io/normalize.css/)
