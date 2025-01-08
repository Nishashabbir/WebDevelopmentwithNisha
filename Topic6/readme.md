creating three boxes and using transform properties on it 

before giving the transform property which can be like rotate , skew , translate or scale we can give the origin of our own choice if we don't want to keep it simple like default origin is given 
transform origin have three axis ;


transform-origin: x-axis y-axis z-axis;
you can give them in pixels and also use simply top left bottom right as origin 

after giving the origin you give the transform value of your choice for example rotate;
e.g
transform-origin: left top;
transform: rotate(45deg);

e.g 
transform-origin: 20px 50px;
transform: scale(1.5);

e.g
transform-origin: 25% 75%;
transform: rotate(45deg);

Four cases :
1-
Rotating a Door (Hinge Effect):

transform-origin: left center; /* Hinge on the left edge */
transform: rotate(90deg);
2-
Scaling an Element from a Specific Corner:

transform-origin: top right;
transform: scale(1.5);

3-
Creating a Pendulum Swing:

transform-origin: top center;
animation: swing 2s infinite;

4- 
3D Card Flip:

transform-origin: center back;
transform: rotateY(180deg);

we can also Combine transform-origin with animations (e.g., @keyframes) for dynamic effects , we'll study later on  