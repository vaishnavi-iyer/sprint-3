What happens to the layout when you resize the screen to less than 550 px. How do you think that works?<br>

When I reduce the screen size to less than 50 px, there are many notable changes in the web page.<br>

1. Everything in the screen is changed to centre aligned including the button " Try Skeleton" which was eft aligned with respect to the text.

2. The overlaying iPhone images now merge to become one. and they are also now under the try skeleton button as opposed to being inline with them.

3. The 67%, 90%, & 66% and their respective description are now stacked vertically as opposed to horizontally.

4. The responsive images are also stacked vertically as opposed to horizontally before.

If you carefully observe the code in custom.css file, you can notice that: <br>
1. The section padding is increased as oer the increase in the screen size. <br>
2. The position, the size and the overall image of the iPhone is increased as per the increase in the screen size. <br> 
3. The padding in the class hero is increased and the heading is also increased. <br>
4. Also, for screens larger than 750 px, the margin and padding of the section class is reduced so that the images are inline as opposed to beng aligned vertically. 
