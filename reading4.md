# Reading 4 - Structure Web Pages with HTML

## Wireframing

- Wireframing can be done by hand or with a tool, such as Invision or Balsamiq
  - [Free Wireframing Tools](https://careerfoundry.com/en/blog/ux-design/free-wireframing-tools/)
- Wireframing by hand gives the advantages of speed and ease of modifications
- Be sure to have user flow mapped out
- Test wireframe with users (test for usability, simplicity, identify places for tooltips)

## Anatomy of an HMTL Document

- <!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However, these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
- \<html></html> — the \<html> element. This element wraps all the content on the entire page and is sometimes known as the root element.
- \<head></head> — the \<head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
- \<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
- \<title></title> — the \<title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
- \<body></body> — the \<body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

## HTML Semantics

- Semantics are important to let the browser know how to best understand the content
- Use the most appropriate tag rather than styling
- Semantics can influence SEO information, such as for page search rankings
