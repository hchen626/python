# Things that I came across on AB Testing #

I recollect what I learned from school (Frequenist view). I recently dusted off my good old statistic textbook, so I can find some more info Bayesian view. I'll continue to review and update what I find. Use the example code at your own risk. Not everything in the notebook is able to render when you preview the book on website, so you probably need to download the notebook. I am using Juypter 6.1.4 by the way.

### Summary on this Topic ###
What I found on the internet is:

"In summary, the difference is that, in the Bayesian view, a probability is assigned to a hypothesis. In the frequentist view, a hypothesis is tested without being assigned a probability."

"Update your prior distribution with the data using Bayes’ theorem (though you can have Bayesian methods without explicit use of Bayes’ rule—see non-parametric Bayesian) to obtain a posterior distribution. The posterior distribution is a probability distribution that represents your updated beliefs about the parameter after having seen the data"

[Click here](https://cxl.com/blog/bayesian-frequentist-ab-testing/#:~:text=In%20summary%2C%20the%20difference%20is,without%20being%20assigned%20a%20probability.)


### Intro to Bayesian AB testing with Will Barker ###
I wrote a Juypter notebook based on his presentation. I also added some code to graph the beta distributions, which he didn't he show. 

I still need some time to review his thoughts. The hypothesis testing from what I am seeing in my text book talks about whether the probability of parameter being in the null or alternative set.

[Click here](https://www.youtube.com/watch?v=nRLI_KbvZTQ)

### Another article on this topic ###
I didn't feel like downgrading my python to 3.7, so I couldn't run his chainconsumer code.

I don't quite understand his formula when he goes into Bayesian. I believe he wrote in wrong in the image.

I agree with his point-of-view on the T-Test though. I added some background to help follow his thought process.

[Click here](https://cosmiccoding.com.au/tutorials/ab_tests)
