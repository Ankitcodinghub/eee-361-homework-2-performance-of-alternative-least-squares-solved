# eee-361-homework-2-performance-of-alternative-least-squares-solved
**TO GET THIS SOLUTION VISIT:** [EEE-361 Homework 2-Performance of alternative least squares Solved](https://www.ankitcodinghub.com/product/eee-361-homework-2-performance-of-alternative-least-squares-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94163&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE-361 Homework 2-Performance of alternative least squares Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In this homework you will investigate the performance of alternative least squares solvers for Ax = b. The numerical techniques to be compared are

• Generalized Minimum Residual (GMRES) • Conjugate Gradients (CG)

• A+: The Pseudoinverse

The first step is to generate a symmetric matrix A according to the example attached in the following pages (from the book Numerical Linear Algebra by Lloyd N. Trefethern and David Bau). You will use the values τ = 0.1 and τ = 0.01 and for each of them you need to create a matrix A with dimensions 100×100, 500×500 and 10000 × 10000 (if the computations with this size create problems in your computational tools, find the largest matrix size for which you can still obtain the results) as explained in the example. So, in total there will be 6 different matrices A.

Now, for each A with dimensions m × m, the next step will be to generate 10 samples of vector x0 by using randn(m, 1). Note that the vector x0 ∈ Rm is sampled from a standard normal distribution. Then, you need to compute b0 = Ax0 and subsequently create the vector b = b0 + w, where w = σw · randn(m, 1) is a vector sampled from a normal distribution with standard deviation σw. You will do this for three different values of σw , namely 0.0001, 0.01, 1. So in total, there will be 30 different realizations of the vector b, corresponding to the 3 different noise levels. Let us denote them by bi,j , for 1 ≤ i ≤ 3 and 1 ≤ j ≤ 10. Note that the value i is the noise level index and j is the index of the realizations of x0.

At this point, you will employ the three methods in order to approximate the least squares solution xˆi,j to the system Ax = bi,j and define the error vector ei,j = (−xˆi,j + x0,j ). Now, for 1 ≤ i ≤ 3, we define

􏰃􏰂1 10 􏰃􏰂1 10

ES,i =􏰂 􏰀∥ei,j∥2 and EO,i =􏰂 􏰀∥bi,j −Axˆi,j∥2 . 􏰁10 2 􏰁10 2

j=1 j=1

ES,i corresponds to the root-mean squared error on the estimated solution, while EO,i corresponds to the root- mean squared error in the fit to the observations. For each different A and the three methods, you will plot the log values of ES,i with respect to the three values of σw. What do you observe? Comment on the results. In the case of the Conjugate Gradients you will also plot the values of EO,i with respect to those of τ, as the plot shown in the example below. Moreover, when you are using the GMRES and Conjugate Gradient approaches:

<ol>
<li>Comment on the stopping criteria you used and investigate what happens if you choose less or signifi- cantly more iterations.</li>
<li>Check the orthogonality of the bases the algorithms generate for the Krylov subspace along with the iterations.</li>
</ol>
For efficient solution to the tridiagonal system generated in GMRES algorithm, you can use efficient algorithms such as Tridiagonal matrix algorithm.

</div>
</div>
</div>
