# Notes on CSS Transforms

## Introduction

- CSS transforms allow developers to manipulate and transform elements in various ways, including scaling, rotating, and skewing.
- Transforms allow for creative and dynamic effects, enhancing the user experience on a website.

## Types of Transforms

- Translate: moves an element along the x and y axis
- Rotate: rotates an element by a specified degree
- Scale: increases or decreases the size of an element
- Skew: skews an element along the x and y axis
- Matrix: combines multiple transforms into one

## Syntax

- `transform: [type of transform](value);`
- Example: `transform: rotate(30deg);`

# Notes on CSS Transitions and Animations

## Introduction

- CSS transitions and animations allow for smooth and gradual changes to elements on a website, rather than sudden jumps or changes.
- These effects can be used to enhance the user experience and add visual interest to a website.

## CSS Transitions

- CSS transitions allow for a gradual change from one property value to another.
- To create a transition, set the `transition` property on the element to be transitioned, specifying the property to be transitioned, the duration of the transition, and any other optional values.
- Example: `transition: background-color 1s ease;`

## CSS Animations

- CSS animations allow for more complex and dynamic effects, including keyframe animations and multiple stages of animation.
- To create an animation, use the `@keyframes` rule to define the stages of the animation, then apply the animation to the element using the `animation` property, specifying the name of the animation, duration, and other optional values.
- Example: 

# Examples of CSS Transitions and Animations

- CodePen examples:
  - http://codepen.io/dp_lewis/pen/gCfBv
  - http://codepen.io/retyui/pen/ByoaXV
  - http://codepen.io/akshaychauhan/pen/oAfae
- WebDesignerDepot article with 8 simple CSS transitions:
  - http://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users

# CSS Transforms, Transitions, and Animations

## CSS Transforms
- Allows the developer to manipulate and transform elements in various ways.
- Example: `transform: rotate(45deg);` to rotate an element by 45 degrees.

## CSS Transitions
- Allows for smooth and gradual changes to elements on a website.
- Example: `transition: background-color 1s ease;` to transition the background color of an element over 1 second.

## CSS Animations
- Allows for complex and dynamic effects, including keyframe animations and multiple stages.
- Example: 
@keyframes slidein {
from { transform: translateX(-100%); }
to { transform: translateX(0); }
}
.element { animation: slidein 1s ease; }

## Differences
- Transitions are for gradual changes, while animations are for more complex and dynamic effects.
- Animations use `@keyframes` to define stages of the animation, while transitions do not.

## Benefits
- Adds visual interest and enhances user experience.
- Allows for smoother and more gradual changes.
- Can be used to draw attention to elements on a page.

## Long-term Goals
- Could be useful for creating visually appealing and dynamic websites.
- Relevant for web development and front-end design. 

