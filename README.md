# the_Mathematician

My mathematics journey. Please enjoy!

## Questions:

A good mathematician can solve problems. A great mathematician can ask the right questions. I have always been told this in school. It makes sense. There are alot of questions in the world that can be observed mathematically in the world, but what is to gain if solved? I will brainstorm some questions that I find interesting in my day to day life. Questions that I will find the answer particularly interesting. Perhaps these questions have already been solved, but I will still present them.

### Word Match
A lot of analyst work with words. Although numbers are much easier to work with these words sometimes need to be searched with different databases (or sets). However words unlike numbers can't be matched so easily. For example, just the slightest letter can throw everything off. If you are trying to match the word "Thomas J" with "Thomas J." it most likely will not match. Of course we can go through the list of names and take away "." value to match, but we will still have the cases like matching "Thomas J" with "Thomas Joseph" or "J Thomas" with "Thomas J". There are many more difficulties that arise with this. So my questions is as follows:

   Is there a way to approximate that two words will match to some percentage given the information from each word in letters?

### Finding the Null Space
This next one is a problem that was presented in my accounting adventure. We were given a list of numbers and I needed to find the sums that added to 0. I call this finding the Null Space. However there are so many numbers that the basic algorithm of finding the number of combinations would be too slow. So the question is as follows:

   Is there an efficient way, given a list of numbers, to find the Null Space. (I.E. the maximum numbers that add to 0)?
    
### Financial Patterns
The other day I was looking into patterns that arise in financial cashflows. These cashflows change the balances in the account. The balance will rise, and the balance will fall. So I did as every intellectually curious mathematician would do by trying to see if I could find a pattern. I tried to see if I could control the time series B(t) (Balance vs Time) by finding a function f where I could minimize the variance of f Var(f(B(t))). I found some things out, but I wasn't sure if there are already a pdf (probability distribution function) out there. My question:

   Do financial patterns follow a certain pdf, and if so how can we find out such a pdf?
   Do other patterns follow a pdf, and if so how can we calculate such pdfs?
   How do we calculate all such pdfs? 
   How do we know there is a better pdf for some given data? 
   Do some sets of data follow multiple pdfs?
   
## Financial Analysis

My favorite way to apply my mathematics is through unpredictable patterns in pricing and balances. Basically any quantitative value I can get my hands on that aren't obviously predictable. An example is a stock price or what the balance for a company will be in a month. 

Lately I have been dealing with a lot of quantitative data. There is a lot of quantitative data available. I want to try to find a trend or pattern. Find a method of a sort so I can predict what is going to happen next. That or be able to come out with some type of measure; that is, to show that a certain set of data has these attributes. I have begin searching for a predictability using Probability, Statistics, and Numerical Analysis. 

The first step I have taken into understanding a set of data is mastering Taylor's Polynomial. Taylor's Polynomial is a way to approximate by a function about a point. This can be useful if a pattern has already been figured out. I can use this to know I have found a pattern. Well I suppose if the pattern is able to be written as a function.

The next step is getting a function from a set of data. I can do this by using interpolation. There are many methods for interpolating points. Interpolation is finding an approximation in the form of a function of some given quantitative data. I should note that this cannot approximate points outside of a the data. This is strictly used for points within the interval of the data. If a pattern does repeat with interpolation we can proceed to use taylor's polynomials to find what will happen next. 

I have already gone over the methods of the basic polynomial interpolation. It seems somewhat straight forward, but computing the polynomial can result in difficulties with computation time and memory storage. This was my first attempt at approximating data, and it isn't a bad approach, however I feel that I am looking for something that doesn't blow up outside of the data points. An interpolation that is more controlled.

Another type of interpolation I have looked into is Lagrange Interpolation. I have no idea where to begin with this. It seems very interesting and can prove useful for predicting stabilized time series or finding a sort of pattern. I have reason to beleive that there are some similarities with this and fourier analysis. Nonetheless I still need more of a conceptial grasp on Lagrange Polynomial before I move further in my studies.

My end goal of all of this is to see what role interpolation has in unpredictable patterns. I understand there is alot of random involved with finance. If a direct pattern cannot be found, then maybe a pattern can be found with predicting the chances that something will happen next; that is, we can predict the probability distribution function.
