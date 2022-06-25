<p class="has-line-data" data-line-start="0" data-line-end="4">Q1=&gt; how to add comments on css?<br>
Ans=&gt; You can add comments on css by using <code>\* */</code> these marks and you can type some information<br>
and some notes between those marks and that thing wont rendered on your browser , it just you are<br>
writing some information for your needs and it will come handy in further process to track.</p>
<p class="has-line-data" data-line-start="5" data-line-end="13">Q2=&gt; Why do we use pseudo-class?<br>
Ans=&gt; Lets say there’s a div or button and we want if take our cursor on that div/button we something happen<br>
like we want to change the background of that div/button in that case we use pseudo-class.<br>
e.g-&gt; div:hover{<br>
background-color: red;<br>
width:200px;<br>
transition: all 2s<br>
}</p>
<p class="has-line-data" data-line-start="14" data-line-end="18">Q3=&gt; How is specificity applied?<br>
Ans=&gt; When there are more than one css properties applied on the same tag, so what happnes now that ,<br>
that tag will take only that css property whose specificity is high and that css rule will be apply<br>
on that certain tag.</p>
<p class="has-line-data" data-line-start="19" data-line-end="22">Q4=&gt;  What method allows an element to be moved from its current position?<br>
Ans=&gt; In this case we can use a property called transform:translate().<br>
we can pass x-axis and y-axis as parameters in translate(x,y) like this.</p>
<p class="has-line-data" data-line-start="24" data-line-end="27">Q5=&gt; What is the diffrenece between flex and girds?<br>
Ans=&gt; Grid is made for two-dimensional layout while Flexbox is for one. This means Flexbox can work on<br>
either row or columns at a time, but Grids can work on both.</p>
<pre><code> Major Uniqueness between Flexbox and Grids is that the former works on content while the latter is 
based on the layout.

 CSS Grids helps you create the outer layout of the webpage. You can build complex as well responsive
 design with this. This is why it is called ‘layout first’. Flexbox mostly helps align content &amp; move blocks.
</code></pre>
<p class="has-line-data" data-line-start="34" data-line-end="39">Q6=&gt; Give an example where we have to use grids and where you have to use flexbox?<br>
Ans=&gt; Grid property are basically used for make a more complex layout.<br>
lets say there are some div’s and you want to place them side by side you can do this with flex property but the<br>
thing is there are most of the time where you need set that how many div’s you want in one row so you can achieved this by<br>
using grid over flex property you can also set how many row’s you want.</p>
<p class="has-line-data" data-line-start="40" data-line-end="42">Q7=&gt; What does rotate do?<br>
Ans=&gt; The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.</p>
<p class="has-line-data" data-line-start="43" data-line-end="46">Q8=&gt; What does object-fit do?<br>
Ans=&gt; The CSS object-fit property is used to specify how an &lt;img&gt; or &lt;video&gt; should be resized to fit its container.<br>
these properties are used for set img in container where we can set how much we want to fit in that.</p>
<p class="has-line-data" data-line-start="47" data-line-end="50">Q9=&gt; What does @media do?<br>
Ans=&gt; @media is used to make our website align perfectly on lappy screen , mobile screen and there are also screens where we need to make our website<br>
align perfectly on every screens.</p>
<p class="has-line-data" data-line-start="51" data-line-end="62">Q10=&gt; How can you select every alternate elements in a list of elements using css?<br>
Ans=&gt;  ul{<br>
list-style-type: none;<br>
color: white;<br>
}<br>
li:nth-of-type(odd){ // or you can also use li:nth-child(odd)<br>
background-color:blue;<br>
}<br>
li:nth-of-type(even){<br>
background-color:red;<br>
}</p>