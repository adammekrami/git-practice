**Adam Mekrami**

## Article: [YAGNI](https://martinfowler.com/bliki/Yagni.html)    

I found this article interesting as it explains the software development principle, YAGNI (You aren't gonna need it"), through an economic lens rather than a pure abstract engineer lens. The author, Martin Fowler, explains that building certain features before they are truly necessary can result in future financial liabilities.

He explains that with building unnessary features, there are two costs that can be incurred. One being the cost of delay which is losing real revenue because you prioritized the wrong thing. The second is the cost of carry which is how unnecessary code slows down every other feature.

### Comment by Hanzalah Siraj

Adam, your economic framing is what made this article land for me. Treating an unnecessary feature as a financial liability rather than just untidy work changes the conversation. Cost of delay is lost revenue you never recover, and cost of carry reads like interest on a loan you never needed to take out - every speculative feature keeps taxing the team's budget of time and attention long after it ships.

I have felt the same tradeoff in machine learning projects. Building a flexible pipeline for experiments that might happen later is essentially paying an insurance premium against a future that may never arrive. Sometimes the policy pays out, but often the premium - the extra complexity everyone has to understand and work around - costs more than the risk ever would have. Fowler's caveat that YAGNI is not an excuse to neglect refactoring fits the financial lens too: refactoring is routine maintenance spend, which is a very different line item from speculative investment.


