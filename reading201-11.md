# Reading: Class 11 - Audio, Video, Images & Grids

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

   In the early days of the web Flash and Silverlight we're used to display media such as video and audio, but there were many security issues with those plug-in based technologies. It is now possible to present the media natively in HTML using the elements \<video> and \<audio>.

2. Describe the use of the src and controls attributes in the \<video> element.

   - src - used to reserve the path/url to the video file
   - controls - gives the user an interface to control the playing of the video

3. Why is it important to have fallback content inside the \<video> element?

   The fallback content is presented to the user if their browser does not support the \<video>
   element, as a direct link to the video file.

4. Write a very short story where \<audio> and \<video> are characters.

   "Hi, I'm \<video>. Some of my possible attributes are width, height, replay, muted, poster and
   controls."
   "Oh yeah? Well, I'm \<audio> and I'm just like you with all the attributes, except maybe width,
   height, and poster."

## The Grid

1. How does Grid layout differ from Flex?

   Grid is a two-dimensional grid layout system, while Flex is a one-dimensional flow layout system. Grid gives more flexibility and functionality than Flex, but the two can be used together with to solve some presentation challenges.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid Please describe these terms in a few sentences.

   - Grid container - The HTML element that is the direct parent of the grid and that has the
     property _Display: grid_.
   - Grid item - The direct child elements of the grid container.
   - Grid line - These are the dividing lines that make up the structure of the grid.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers
   make images responsive?

   Responsive images ensure important content is being focused on, as well as giving a visually pleasing layout.

2. Define the following \<img> attributes _srcset_ and _sizes_. Write an example of how they are
   used.

   - _srcrset_ - a string that contains alternate image files and sizes, used to help the browser
     present more size appropriate content
   - _sizes_ - a string that contains image size criteria to tell the browser when to use alternate
     images

3. How is _srcset_ more helpful for responsive images than CSS or JavaScript?

   Images are loaded before CSS or JavaScript are applied, meaning that the browser doesn't
   have the opportunity to load a smaller, faster-loading image, if that would have been the best
   one for the viewport size.

## Things I want to know more about

I'm just excited to start working with grids in projects.
