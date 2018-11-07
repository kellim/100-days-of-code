# 100 Days of Code: Round 1

![100 Days of Code Round 1 Image](assets/images/100-days-of-code-round-1.jpg)

This is my log for the [100 Days of Code](https://www.100daysofcode.com/) challenge that I started on 11/4/18. 

## Day 3: November 6, 2018

![100 Days of Code Day 3](assets/images/100-days-of-code-day-3.jpg)

**Progress:** I spent some time barking up the wrong tree on how to vertically align an image next to the text inside the carousel, and in the end I figured out that Flexbox is probably the way to go even though I'd previously ruled it out. 

I thought that Flexbox wouldn’t work inside the carousel before, but I just needed to add another wrapper div inside the carousel item. You don’t want to use Flexbox on the div with the class “item” inside a carousel or else it will display both of the items at once. I haven’t looked at the Bootstrap 3 source code, but it probably uses `display` to hide the item that doesn’t have the `active` class applied to it.

Unfortunately, CodePen lost my progress where I got it to work so I’ll have to redo it tomorrow. And there’s still a challenge with this in getting the image to go on top of the testimonial text on small viewports, but I’ll leave that for tomorrow.


**Links:**
* [Bootstrap Testimonial Carousel with kittens on CodePen](https://codepen.io/kelli/pen/eQmeyV) - still a work in progress.



## Day 2: November 5, 2018

![100 Days of Code Day 2: Learning by Doing](assets/images/100-days-of-code-day-2.jpg)

**Progress:** I worked on my CodePen carousel again today and did a lot of troubleshooting. I'm happy that now only one testimonial is showing at a time and clicking the arrows to display the next or previous testimonial works as well. 

I wanted to use Flexbox to style the carousel items, but I found out that using Flexbox in Bootstrap 3 carousel items is problematic so I'm using the Bootstrap grid system instead and struggled a bit with making sure the gap between columns wasn't too big.

The next thing I need to do is adjust the height of some elements using JavaScript so that I can center a carousel item's image next to a blockquote and make it so the content under the testimonials section doesn't move up or down since the testimonials are different sizes. I spent a lot of time trying to figure out how to do this without JavaScript since some people might have JavaScript turned off, but I'm sure now that JavaScript is the way to go in this case.

I feel like I should have finished this already, but I'm learning from the experience and that's what matters!

**Links:**
* [Bootstrap Testimonial Carousel with kittens on CodePen](https://codepen.io/kelli/pen/eQmeyV) - a work in progress.

## Day 1: November 4, 2018

![100 Days of Code Day 1: Coding with Kittens](assets/images/100-days-of-code-day-1.jpg)

**Progress:** Today I worked on a Testimonial carousel using Bootstrap for the [She's Coding website](http://shescoding.org/). I'm having trouble formatting it properly and made an example version on CodePen with kittens to play around with, but it's not working yet. I added two testimonials and you can see them both at the same time, but you're supposed to be able to click arrows to switch between the two. 

I also setup this 100 Days of Code Log to be on [GitHub Pages using a Jekyll theme](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/), and I customized the theme a little. The easiest theme to use for 100 Days of Code is the [leap-day](https://github.com/pages-themes/leap-day) theme because it will put everything with a heading in the sidebar list, so it's like a mini blog and you can still put your entire 100 Days of Code log into one markdown file.

**Links:**
* [100 Days of Code on GitHub Pages](https://kellim.github.io/100-days-of-code/round1) - you might already be on this page if not viewing this as a Markdown file on GitHub!
* [Bootstrap Testimonial Carousel with kittens on CodePen](https://codepen.io/kelli/pen/eQmeyV) - it's not working yet, but it's got kittens!

**Kitten Links:**
* [Cat Ipsum](http://www.catipsum.com/)
* [placekitten](https://placekitten.com/)
