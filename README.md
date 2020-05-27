<h1><strong> Battery-CSS </strong></h1>
<h2>HTML file that includes the CSS for the charging and discharging of a battery</h2>
<h1><strong> Keyframe Circle </strong></h1>
<h2> CSS for basic explanation of @Keyframes property</h2>

<p><span class="text-big">CSS allows animation of HTML elements without using JavaScript. An animation lets an element gradually change from one style to another. You can change as many CSS properties you want, as many times you want. To use CSS animation, you must first specify some @keyframes for the animation. @keyframes hold what styles the element will have at certain times.&nbsp;</span></p>

<p><span class="text-big">We will be using a basic example such as the animation of a battery charging.&nbsp;</span></p>

<p><span class="text-big">The @keyframes property has the option to divide the animation time into parts/percentage and perform an activity that is specified, for that part of the whole duration of the animation. the @keyframes property is given to each animation according to the name of that animation. It allows you to run the animation infinitely as well.&nbsp;</span></p>

<p><span class="text-big">Here, is a simple CSS block that explains the usage of @keyframes:&nbsp;</span></p>

<p><span class="text-big"><strong>Examples: Usage of @keyframes in a background-color change</strong></span></p>
<pre><strong>Input : </strong></pre>

    @keyframes circle {
      0%   {background-color: red;}
      25%  {background-color: yellow;}
      50%  {background-color: blue;}
      100% {background-color: green;}
    }
<p><br><span class="text-big"><strong>Note:</strong> While using @keyframes, there are a certain amount of guidelines that are set in place for you to create a smooth and working animation. Guidelines such as, make sure you make the transitions smooth and specify when the style change will happen in percent or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the beginning of the animation, 100% is when the animation is complete. For best browser support, you should always define both the 0% and the 100% selectors.</span></p>

<p><span class="text-big">The animation for the charging of a battery is important, as it helps you to understand just how the @keyframes property will help you to time your animation in perfect intervals and hence help make the transitions smooth. The charging of the battery is used to explain how you can set various animations within the given time-period by specifying the percentage of division, exactly how in the example the battery charges from 0-25% then from 25-50% and so on.</span></p>
<pre><strong>Input:</strong>
</pre>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20200506202219/ezgif.com-video-to-gif19.gif" alt="">
<p><br>&nbsp;</p>

