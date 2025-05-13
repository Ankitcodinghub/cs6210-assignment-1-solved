# cs6210-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS6210 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs6210-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93097&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6210 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Note: Please use Matlab, and its spline toolbox for this assignment . Your code must compile and run on a standard laptop. Document your code. The broad aim of the assignment is to give you fan understanding of the strengths and weaknesses of different kind of polynomial interpolants. Note that the programs that you write may be less than 100 lines.

The specific aim of the assignment is to compute polynomial interpolants for the function exp(x) on [0,2] using evenly spaced and Chebyshev points and with interpolants constructed using the Vandermonde equations, the polyinterp.m routine, the barycentric interpolation routine barylag.m and finally the matlab cubic spline routine pchip and the spline toolbox routines shown in the lectures. This process will enable you to understand which method is the most robust and accurate and how this accuracy varies with the choice of points and also what the cost of the methods is. The Second part of the assignment applies the same methods to a data set taken from weather modeling.

Instructions

<ol>
<li>Write a simple programs to plot the exponential function on the interval [0,2] using 1001 evenly spaced points.</li>
<li>Modify your program to use the Vandermonde matrix to calculate an interpolating polynomial to exp(x) on [0,2] with 6,11,21,41,81,161,321 and 641 points and to evaluate the accuracy at 1001 sample points using the infinity and 2 norms. Use both evenly spaced points and Chebyshev spaced points x(i) on [-1,1] mapped to [0,2] as given by x(i) = 1 –cos(π(i-1)/(n-1)) for i = 1,…,n. Comment on and describe how the accuracy changes with the choice and number of points.</li>
<li>Extend the program to use the Matlab routines polyinterp and barylag that use Lagrange polynomial interpolation . Again comment on how the accuracy varies with the different choice of 6,11,21,41,81,161,321 and 641 points, both Chebyshev and evenly spaced. Note that not all the codes work well fro all choices of points</li>
<li>Further extend your program to use the Matlab cubic spline routine PCHIP with both even and Chebyshev points. Again use both sets of points and comment on the outcome. Is the choice of points so critical for the spline routine as it was for the Lagrange polynomials?</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>Using the matlab timing functions tic and toc, time the 4 different methods with the required points and plot them. How do these timing results compare to each other? Did you see what you expected? On a different graph plot the infinity error norms for the different point sets. Note in order to show and explain your results you may have to exclude certain data points when one or more methods blows up. This may happen with polynomials on a large evenly spaced mesh for reasons we have discussed in class.</li>
<li>Extend your code to the weather model data sets supplied. In this case you have to read in the dynamics points and values from the data file zd and the associated values from the data file ud . There is no known solution for this data set but one measure of accuracy is to evaluate the interpolant at the physics points provided in the data set file zp . A new interpolant is then created at the physics data points using the same interpolation method. This new interpolant is then evaluated back at the original points and a measure of both interpolation errors is provided by the difference between these values and the original values. Also use plots to demonstrate whether of not there are overshoots or undershoots in the first interpolant.</li>
<li>Provide a summary that explains which method provides the fastest answer and is the most accurate and robust for both methods,</li>
</ol>
</div>
</div>
</div>
