# CSS Transforms, Transitions, and Animations

CSS 2D Transforms Methods with the CSS `transform` property you can use the following 2D transformation methods:

- translate()
- rotate()
- scaleX()
- scaleY()
- scale()
- skewX()
- skewY()
- skew()
- matrix()

With the CSS `transform` property you can use the following 3D transformation methods:

- rotateX()
- rotateY()
- rotateZ()

To create a `transition` effect, you must specify two things:

- the CSS property you want to add an effect to
- the duration of the effect

examples:
`transition: width 2s, height 2s, transform 2s;`
`transition: all 2s linear;`

An `animation` lets an element gradually change from one style to another. You can change as many CSS properties you want, as many times you want.
To use CSS `animation`, you must first specify some `keyframes` for the `animation`. `Keyframes` hold what styles the element will have at certain times.

example:

```
/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```
