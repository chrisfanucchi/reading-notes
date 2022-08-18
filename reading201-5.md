# Reading: Class 5 - Images, Color, Text

## Using Images In HTML

1. What is a real world use case for the alt attribute being used in a website?

   The _alt_ attribute contains a string that will be displayed is the image cannot or does not load. Its a textual description of the image.

2. How can you improve accessibility of images in an HTML document?

   Using the _alt_ attribute makes the image "content" accessible to those who cannot see, such as people using screan readers, a search engine that interrogates a site to assess content, or for those with low bandwidth who turn off images.

3. Provide an example of when the figure element would be useful in an HTML document.

   A _figure_ element has self-contained content, like diagrams, photos, code, or illustrations. It's position is normally independent of the main flow.

4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.

   - GIF - an image that is like a photograph, that might include a little bit of motion in it
   - SVG - a more simple, but precise graphic, like a line, a aquare, or a circle, which might colors or other simple attributes applied

5. What image type would you use to display a screenshot on your website and why?

   I would use a PNG file, for precise reproduction and better compression (i.e. file size).

## Using Color in CSS - Styling HTML Text Elements

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

   Foreground color refers to the content itself, such as the text or actual words being displayed. While background color refers to the rest of the content ares that lies behind the actual content or text.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

   - Have the friend select aq base color
   - Flesh out the color palette (use a tool such as [Paletton](https://paletton.com/) or [Adobe Color](https://color.adobe.com/))
   - Also need to add some core neutral colors such as white (or nearly white), black (or nearly black), and some number of shades of gray [^1]
   - There are several articles on color theory, to include [Color Science](https://www.khanacademy.org/computing/pixar/color) and [Color Theory](https://en.wikipedia.org/wiki/Color_theory)
   - Consider accessibility issues (see various web resources)

3. What should you consider when choosing fonts for an HTML document?

   Ensure it is a "web safe font" (i.e. those available across most systems and browsers) - See [Core fonts for the Web](https://en.wikipedia.org/wiki/Core_fonts_for_the_Web) for a compatibilty table for fonts and systems/versions.

4. What do font-size, font-weight, and font-style do to HTML text elements?

   - _font-size_ - changes the size of the text
   - _font-weight_ - set the amount of "boldness" of the text
   - _font-style_ - currently, used to turn italics on or off for text

5. Describe two ways you could add spacing around the characters displayed in an h1 element.

   ```js
   h1 {
      letter-spacing: 2px;
      word-spacing: 4px;
   }
   ```

## Things I want to know more about

I'd like to spend some more time reading up on color theory and the use of effective palettes.

---

[^1]: "Applying color to HTML elements using CSS", https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color
