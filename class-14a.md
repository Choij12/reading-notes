# CSS Transforms, Transitions, and Animations
- `transform` property comes in two different settings
- two dimensional 
- three dimensional 
- new techniques are made possible through transform property 
- browser support isn't best but improving 
- users need to download the nightly version of Chrome to see all of the transforms
- transform property followed by the value
- calue specifies the transform type followed by a specific amount inside parentheses
- includes multiple vendor prefixes to gain the best support
- elements may be distorted or trasnformed
- two dimensional transforms work on the x and y axes 
- three dimensional transforms work on x,y,z
- thee dimensional also define the depth
- `rotate` value provides the ability to rotate an element from 0 -360 degrees
- postive value - rotate clockwise
- negative value - rotate counter clockwise
- default point - 50, 50
- `scale` value within the `transform` property allows the user to change the appeared size of an element
- possible to scale using the `scaleX` and `scaleY` values
- `translate` value works a bit like the relative positioning
- pushes and pulls an element in different direction
- last `transform` value in the group `skew` is used to distort elements
- `skew` cannot be trasnformed on a three dimensional scale
- properties, `rotate3d`, `scale3d`, `transition3d`, and `matrix3d` require math and a strong understanding of matrices
- `transform-style` property needs to be placed on the parent element
- `backface-visibilty` is `visible` and is the deault value, displaying an element 
- not all properties may be transitioned
- timing values for transition duration
- transition-timing function - set speed which a transition will move
- transition-delay - sets delay
- shorthand - supporting all of these different properties and values
- animation - `@keyframe` 
- fade in 
- `grow` - enlarge
- `shrink` - shrink
- `rotate` - rotate 
- `circle` - change square into a circle
- `threed` - 3d shadow
- `@-webit-keyframes swing` - swing animation
