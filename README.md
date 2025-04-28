# cs524-homework-6--quadratic-programs-and-regression-solved
**TO GET THIS SOLUTION VISIT:** [CS524 Homework 6- Quadratic Programs and Regression Solved](https://www.ankitcodinghub.com/product/cs524-homework-6-quadratic-programs-and-regression-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119633&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS524 Homework 6- Quadratic Programs and Regression Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Submit pdf files via Canvas

1. [6 points]

In this problem, you are given a “random” polyhedron

P = {x ∈ Rn | Ax ≤ b},

where ∼ is one of ≤,≥, and b ∈ Rm. You will create each P by choosing its parameters uniformly and randomly in the following intervals:

• bi ∈ [0,100], i = 1,…,m

• aij ∈ [−2,2], i = 1,…,m, j = 1,…,n.

(Note that 0 ∈ P because all the components of b are positive, so we know the polyhedron is nonempty.) Let n = 100,m = 20.

(a) Generate 1000 random points ˆx ∈ Rn whose components ˆxj are chosen randomly from a uniform distribution over [−1,1] for all j = 1,2,…,n. By checking whether or not each of these points lies in P, estimate the probability prob in P of a random point of this type lying in P.

(b) Save one of the ˆx from part (a) that does not lie in P. For this value of ˆx, find the following quantities:

(i) z2 := minx∈P kx − xˆk2

(ii) z1 := minx∈P kx − xˆk1

(iii) z∞ := minx∈P kx − xˆk∞

Recall that

.

Note that the first problem can be solved with convex quadratic programming (convex QP), and the second and third minimum distance problems can be solved with linear programming (LP). Ensure you report scalar outputs for the three projection problems.

Please use set silent(model name) in your code to avoid excessive output. Your code should print only the probability of the point being in P, and the three values of the norm distances to P.

2. [4 points] Quadratic form positivity. You’re presented with the constraint:

2×2 + 6y2 + 2z2 + 4xy − 6xz − 6yz ≤ 1 (1) a) Write the constraint (1) in the standard form vTQv ≤ 1. Where Q is a symmetric matrix. What is Q and what is v?

b) It turns out the above constraint is not convex. In other words, the set of (x,y,z) satisfying the constraint (1) is not an ellipsoid. Explain why this is the case.

Note: you can perform an orthogonal decomposition of a symmetric matrix Q in Julia like this:

(Lambda,U) = eigen(Q) # Lambda is the vector of eigenvalues and U is orthogonal

U * diagm(Lambda) * U’ # this is equal to Q (as long as Q was symmetric to begin with)

1 of 2

c) We can also write the constraint (1) using norms by putting it in the form:

kAvk2 − kBvk2 ≤ 1

What is v and what are the matrices A and B that make the constraint above equivalent to (1)?

d) Explain how to find a vector (x,y,z) that satisfies the constraint (1) and that has arbitrarily large magnitude (i.e. x2 + y2 + z2 is as large as you like).

3. [4 points] Lasso regression. Consider the data (x,y) plotted below, available in lasso_data.csv.

In this problem, we will investigate different approaches for performing polynomial regression.

(a) Perform ordinary polynomial regression. Make plots that show the data as well as the best fit to the data for polynomials of degree d = 5 and d = 15. Also comment on the magnitudes of the coefficients in the resulting polynomial fits. Are they small or large?

(b) In order to get smaller coefficients, we will use ridge regression (L2 regularization). Re-solve the d = 15 version of the problem using a regularization parameter λ = 10−6 and plot the new fit. How does the fit change compared to the non-regularized case of part a? How do the magnitudes of the coefficients in the resulting polynomial fit change?

2 of 2
