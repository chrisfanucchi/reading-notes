# Reading: Class 14a - CSS Transform, Transition & Automation

## CSS Transform

1. What does a CSS transform allow the developer to do to an element?

   It gives a developer new ways to position and alter an element, with the ability od specifying the transforming by browser, and transforming the element on both a 2D and 3D plane.

2. Provide an example of a transform and how you could see that being used on a website.

   ```css
   .image:hover {
     transform: translateX(-10px) translateY(25%);
   }
   ```

   This transform could be use to "pop" out an image when a user mouses over it, to help highlight the currently viewed image.

## CSS Transition & Animation

1. What does a CSS transition allow the developer to do to an element?

   It allows the developer to change the behavior or appearance of an element, sometimes over a specified duration or with a delay, when a certain change of state occurs (e.g. mouse over).

2. How does a CSS animation differ from a CSS transition?

   An animation is like a series of transitions that include milestones, with specific progress, called keyframes. It is used when more specificity is needed in the details of the transition of the element.

## 8 Simple CSS3 Transitions That Will Wow Your Users

1. What are some benefits to using CSS transitions on websites?

   Awesome transitions can, 'excite your users, increase engagement and ultimately, when used well, increase your conversions.' [^1]

2. How this topic fits in with your long-term goals?

   It gives us an example of ways to use CSS to increase the "wow factor" of a website, hoping impressing the client and drawing more of their customers interest and business.

## Things I want to know more about

I would like to play more with transition/automation, such as this button pressing example:

```css
button {
  border: 0;
  background: #0087cc;
  border-radius: 4px;
  box-shadow: 0 5px 0 #006599;
  color: #fff;
  cursor: pointer;
  font: inherit;
  margin: 0;
  outline: 0;
  padding: 12px 20px;
  transition: all 0.1s linear;
}
button:active {
  box-shadow: 0 2px 0 #006599;
  transform: translateY(3px);
}
```

And this card flipping example:

```html
<div class="card-container">
  <div class="card">
    <div class="side">...</div>
    <div class="side back">...</div>
  </div>
</div>
```

```css
.card-container {
  height: 150px;
  perspective: 600;
  position: relative;
  width: 150px;
}
.card {
  height: 100%;
  position: absolute;
  transform-style: preserve-3d;
  transition: all 1s ease-in-out;
  width: 100%;
}
.card:hover {
  transform: rotateY(180deg);
}
.card .side {
  backface-visibility: hidden;
  height: 100%;
  position: absolute;
  width: 100%;
}
.card .back {
  transform: rotateY(180deg);
}
```

---

[^1]: "8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS", https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/.
