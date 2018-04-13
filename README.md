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

## Risk Analysis

Mathematics can make choices kind of dull. What I mean by this is knowing the "best" solution can make choosing any other decision wrong. And once the problem has been solved after the same "best" solution has been implemented and routinely practiced it seems like there is no room for growth. It just becomes a dull set of routinely practiced optimized set of decisions. 

That's what makes Risk Analysis so fun. The decision might be the "best" solution but it is unpredictable what is going to happen next. Also alot of the time there is no "best" solution. Sometimes it comes down to risk for reward. That is what makes it thrilling. The mathematical observation of what a mathematician thinks will happen and what actually happens. If the mathematician is lucky enough to pin the tail on the donkey and find the true probabilities of the outcomes he is observing, then he can still ride along with the unpredictability. 

For example, if we know a coin was going to land on heads 60% of the time, and we put $5 dollars that heads is going to win. Let that if heads wins we win $5 and if it loses we lose $5. When should we stop? Certainly we want to make as much as possible so the mathematical solution would be as much as possible, but is this possible? And sometimes it is about the journey. If we keep betting and keep winning more than 60% of the time should we walk away. And if so to what winnning percentage can we agree that we will most likely never reach this point again. It could also be the case that we lose all of our money in the first spins because they all land on tails. Anything is possible even though it isn't probable.

When you put this scenarios in a business standpoint we can't ever reach the point of being bankrupt. Not even close to 1% becuase that would mean over a long period of time the company will eventually go bankrupt! So in a practical sense we have to avoid every catstrophic event of failure while maximizing our profitability. This is for a business standpoint. From a personal standpoint you might want to maximize your profitability without even glancing at the thought of bankrupcy.

The adreneline of risking money for more money. The journey it brings, and the rewards it reaps are what make risk analysis exciting. And when I say risk analysis I don't just mean risk analysis I mean the application of risk analysis. Identifying the probabilities (pdfs) and what is the optimized routes are usually the easy part. The real difficulty is when to call it quits, and when to put more on the table.

## To Which Measure

A lot of the times in the workplace we have goals that we would like to achieve. In order to achieve these goals we try different methods and strategies. But how can we measure that our strategy is actually making progress, and if not when we can conclude that it is actually hurting the company? Mathematically I see this is as a form of measure theory. Measure theory is pretty basic, and is built off of two axioms. The two axioms are that the sum of the parts add up to the whole, and that for any additional sum the total stays the same or grows. Pretty straight forward, but the challange is finding what we are trying to measure.

Measures can be built off of variables. As an example I will use the variables time and money. The most valuable resources in the world. Let us say we have a method to make money. The method requires time, and as a measure goes the more time we put in the amount of money we have will either stay the same or grow. So we can see this as a cumulative growth of all the money we made or the area under the curve of the money we made at particular times. I hope you can see the picture of the graphs. It is pretty unpredictable and looks like a discrete function for both the cumulative form and activity form.

Now if we focus on the graph that displays the activity we can see that the graph will rise and fall. The measure we put on this graph is the area under the curve (or integration for those with calculus background. I want to also extend the curiousity that this could simply be a multiplication between two functions, one of time and one of money). Calculating the area isn't precisely what we are concerned with. What we are concerned about is how do we measure the efficiency of this graph? How can we track the progress we have made; that is, how do we know we are making more money over time? Theoretically we want to achieve 100% of what is possible, so perhaps we can look at this graph and ask "What could have been the maximum amount of money that was available?". The only problem with this question is that most of the time outside of theory we don't know the maximum potential. If we knew the maximum potential area we could divide the area we measured our progress and divided it by the maximum possibility. In this scenario we would shoot for 100%

So this is where my road ends. Yes we are able to compare against ourselves to see our progress as a company, but how do we find a ratio measurement that shows that we can do better. That we are not the best even though we are making progress, or to how good we are with respect to maximum efficiency. There could be documents out there that solve this question, but for now I shall let my mind wonder.

## Forecasting

One major topic in mathematics is forecasting (aka extrapolation, approximation theory, or predictive analytics). It is basically taking a set of points with respect to some given time frame, and trying to predict the next point. Now there are two approaches that come to mind whenever trying to "predict" the next point. One is using fourier analysis and the other is probability.

The first approach we can use polynomial interpolation with trignometric functions. This is also called fourier analysis. This works really well if patterns tend to repeat themselves. Furtheremore if you are dealing with truly unpredictable data, then this will most likely be jibberish. 

The second approach is using intervals and finding the probablility that the next point will be in particular locations. This is excellently paired with the prior, since if the pattern is highly leaned in one direction or the other it will reveal itself. The method used for this is Guassian Process. In fact this is a huge topic in machine learning if I'm not mistaken. 

It creates an infinitely deminsional normal distribution out of only finitely many points. More details I will not be able to explain until I jump into the juicy topic myself.
