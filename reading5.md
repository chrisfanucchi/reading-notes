# Reading 5 - Design Web Pages with CSS

- CCS rules open with a Selector and then declarations (properties and values) within {}
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS) includes browser compatibility tables for each property
- There are three ways of inserting a style sheet:
  - External CSS (\<link rel="stylesheet" href="mystyle.css">)
  - Internal CSS (between \<style> tags)
  - Inline CSS (using style="” in the tag itself)
- Internal styles are defined after the link to an external style sheet
  - Except when the internal style is defined before the link to the external style sheet
- All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:
  1. Inline style (inside an HTML element)
  2. External and internal style sheets (in the head section)
  3. Browser default
- [W3C Schools CSS Reference/Tutorial](https://www.w3schools.com/css/default.asp)
