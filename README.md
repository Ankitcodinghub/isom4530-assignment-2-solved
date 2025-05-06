# isom4530-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [ISOM4530 Assignment 2 Solved](https://www.ankitcodinghub.com/product/isom4530-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97521&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISOM4530 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
I. This problem analyzes the daily Hang Seng Index data.

<ol>
<li>Create a vector DHSIRET containing the daily raw returns. Recall that the raw return on a given day is the difference between the value on that day and the day before divided by the value on the previous day. Compute the mean and standard deviation of daily raw returns.</li>
<li>Conduct an exploratory data analysis using the function eda.shape. Comment.</li>
<li>Fit GPD to the returns, give detailed procedure including how to specify the tails and
check the model fitting. Discuss the fitting results.
</li>
<li>Generate a sample of size 10,000 from the GPD fitted above. Call this sample S DHSIRET,
produce a Q-Q plot of DHSIRET against S DHSIRET, and comment.
</li>
<li>Compute the VaR at the level of 0.005
(a) using empirical quantile;

(b) assuming that the daily raw return is normally distributed;

(c) using the fitted GPD distribution;

(d) using the Monte Carlo sample S DHSIRET that you generated.

Explain the differences and similarities between the estimates of VaR so obtained.
</li>
<li>Compute the expected shortfall at the level of 0.005
(a) using empirical conditional mean;

(b) assuming that the daily raw return is normally distributed;

(c) based on the fitted GPD distribution.

Explain the differences and similarities between the estimates of expected shortfall so obtained.
</li>
</ol>
Note: The HSI data can be downloaded from Canvas. The necessary commands are available in “gpd code.R”.

II. Parts 1 &amp; 2 of Problem 3.7 on page 187 of the book by Carmona. (cf. Lect 6)

Note: The data UTILITIES can be downloaded from Canvas. You can use the following command to load the data:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
ISOM 4530, Fall 2020 2

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>UTILITIES&lt;-read.csv("UTILITIES.csv")
X &lt;- UTILITIES[ , 1 ]
Y &lt;- UTILITIES[ , 2 ]
</pre>
Hint for part 2: if X and Y are jointly normal, then any linear combination of them is also normal.

III. (cf. Lect 6 p.29-48)

<ol>
<li>Generate a sample of size n = 1024 from the distribution of N(0,1) (call X the vector containing the sample values). Construct a vector Y with each entry being the square of the corresponding entry of X. Produce a scatterplot of all the points (xi, yi). Give a guess of how big the sample correlation might be (no need to report). Compute the sample correlation ρ􏰀(X, Y ) using R (command: cor). Is it close to your guess? (no need to report)</li>
<li>Generate a sample from the distribution of N(3,1) of size n = 1024 (call XX the vector containing the sample values). Construct a vector Y Y with each entry being the square of the corresponding entry of XX. Produce a scatterplot of all the points (xxi,yyi). Give a guess of how big the sample correlation might be (no need to report). Compute the sample correlation ρ􏰀(XX,YY) using R. How was your guess? (no need to report)</li>
<li>Compute the correlation coefficient of two random variables A ∼ N(μ,σ2) and B = A2. Hint: Recall that if A ∼ N(μ,σ2), then A can be written as A = μ+σZ where Z ∼ N(0,1).
Also, if Z ∼ N(0,1), then E(Z) = E(Z3) = 0, E(Z2) = 1, and E(Z4) = 3.
</li>
<li>Consider the setting of the above question with μ = 0. Are A and B uncorrelated? Are A and B independent?</li>
</ol>
</div>
</div>
</div>
