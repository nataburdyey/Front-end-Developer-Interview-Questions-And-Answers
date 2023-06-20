---
title: CSS Questions
layout: layouts/page.njk
permalink: /questions/css-questions/index.html
---

<details>
  <summary>
    <b>What is CSS selector specificity and how does it work</b>
  </summary>

CSS selector specificity is a concept that `determines the priority or weight` of a selector in relation to other selectors when applying styles to HTML elements.

Inline styles have the highest specificity, followed by ID selectors, class selectors, attribute selectors, pseudo-classes, element selectors, and pseudo-elements. The only way to override inline styles is by using `!important`.

When multiple rules target the same element, the rule with the higher specificity takes precedence. If two or more rules have the same specificity, the rule that appears later in the CSS file or style block will override the previous rule.

Understanding selector specificity helps in writing more specific and targeted CSS rules, avoiding conflicts, and achieving the desired styling effects.
</details>
<details>
  <summary>
    <b>What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?</b>
  </summary>
  
"Resetting" and "normalizing" CSS are different approaches for dealing with `browser default styles` and inconsistencies.

`CSS Reset`: It removes all default styles, giving developers `full control` over the appearance of elements but requiring explicit styling for all elements.

`CSS Normalize`: It aims to normalize default styles across browsers while `preserving useful defaults`. It provides consistency and addresses browser inconsistencies without removing all default styles.

The choice depends on project requirements and preferences. If you want complete control over styles, use a CSS reset. If you want to maintain some consistency while still having flexibility, use CSS normalize.
</details>
<details>
  <summary>
    <b>Describe Floats and how they work.</b>
  </summary>

Floats in CSS are used to position elements to the left or right, allowing other content to wrap around them. They are commonly used for creating multi-column layouts, image positioning, and text wrapping.

When an element is floated, it is removed from the normal flow of the document and other elements will adjust their position to accommodate it. Floating elements can interact with surrounding elements, such as text wrapping around a floated image.

However, floats can also introduce some challenges, such as collapsing parent containers and requiring the use of clearing techniques to prevent unwanted effects. In modern CSS, floats are often used in conjunction with other layout techniques like Flexbox or CSS Grid.
</details>

- Describe z-index and how stacking context is formed.
- Describe BFC (Block Formatting Context) and how it works.
- What are the various clearing techniques and which is appropriate for what context?
- How would you approach fixing browser-specific styling issues?
- How do you serve your pages for feature-constrained browsers?
- What techniques/processes do you use?
- What are the different ways to visually hide content (and make it available only for screen readers)?
- Have you ever used a grid system, and if so, what do you prefer?
- Have you used or implemented media queries or mobile specific layouts/CSS?
- Are you familiar with styling SVG?
- Can you give an example of an `@media` property other than `screen`?
- What are some of the "gotchas" for writing efficient CSS?
- What are the advantages/disadvantages of using CSS preprocessors?
  - Describe what you like and dislike about the CSS preprocessors you have used.
- How would you implement a web design comp that uses non-standard fonts?
- Explain how a browser determines what elements match a CSS selector.
- Describe pseudo-elements and discuss what they are used for.
- Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
- What does `* { box-sizing: border-box; }` do? What are its advantages?
- What is the CSS `display` property and can you give a few examples of its use?
- What's the difference between inline and inline-block?
- What's the difference between the "nth-of-type()" and "nth-child()" selectors?
- What's the difference between a relative, fixed, absolute and statically positioned element?
- What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
- Have you used CSS Grid?
- Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
- Have you ever worked with retina graphics? If so, when and what techniques did you use?
- Is there any reason you'd want to use `translate()` instead of _absolute positioning_, or vice-versa? And why?
- How is clearfix css property useful?
- Can you explain the difference between px, em and rem as they relate to font sizing?
- Can you give an example of a pseudo class? Can you provide an example use case for a pseudo class?
- What is the difference between a block level element and an inline element. Can you provide examples of each type of element?
- What is the difference between CSS Grid and Flexbox? When would you use one over the other?
