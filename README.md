# Portfolio Optimization Project

In this project, i aim to create an optimal portfolio by using Markowitz Mean Variance model with some financial analysis techniques. My study will focus only on equity market. 

Mean Variance portfolio optimization is a well-known technique in modern finance theory. This technique is based on covariances between different assets and give you optimal weights to invest those specific assets (in my case stocks) by investors' risk preferences. In mean variance optimization, investors have 2 main action: keeping their return at a level and try to minimize risk (risk averse portfolio) or keeping their risk at a level and try to maximize return (return portfolio). I will try to create many portfolios to create an efficient front an choose the best return portfolio on that graph. 

One of the main problem of Markowitz Portfolio Optimization is that it focuses only on stock price movements, regardless of what characteristics the companies have. After all, stocks are essentially a means of being a shareholder of a company. But this method does not care about firms' financial situation, profitability, capital structure, growth opportunities etc. 

For these reasons, i aim to add another step into this process which is a Multi Criteria Decision Making (MCDM) method called TOPSIS (Technique for Order Preference by Similarity to An Ideal Solution). Multi-criteria decision making (MCDM) refers to making choice of the best alternative from among a finite set of decision alternatives in terms of multiple, usually conflicting criteria. The main steps in multi-criteria decision making are the following

– establish system evaluation criteria that relate system capabilities to goals,
– develop alternative systems for attaining the goals (generating alternatives),
– evaluate alternatives in terms of criteria,
– apply one of the normative multiple criteria analysis methods,
– accept one alternative as “optimal” (preferred),
– if the final solution is not accepted, gather new information and go to the next iteration of multiple criteria optimization. 

In my study, i will use TOPSIS method to evaluate firms in a financial analysis perspective by using some firm-level characteristics. TOPSIS method process basically as follows;
construct a decision matrix (first column consist of alternatives-firms and each column will consist of different evaluation criteria), normalization of decision matrix, calculate weighted normalized decision matrix, determine positive and negative ideal solutions, calculate the separation measures from the positive ideal solution and the negative ideal solution, calculate the relative closeness to the positive ideal solution and lastly rank the preference order.

**In this ordering i will choose 50 best firms to use in Markowitz Portfolio Optimization.**

I choose 6 evaluation criteria to use in TOPSIS method;
- Growth (Total assets growth),
- Profitability (Return on sales, return on assets),
- Liquidty (Liquidty ratio),
- Stock price level (P/E, MV/BV, MV/Sales),
- Capital Structure (Debt/Total Assets). 
I will use these criteria to assess 100 firms in Istanbul Stock Exchange. 

To conclusion, i will imply TOPSIS method which is a Multi-Criteria Decision Making method to evaluate and select best 50 firms in Istanbul Stock Exchange. Afterwards, by using stock price movements of these best 50 firms, i will construct a Markowitz Portfolio Optimization model and select the best return portfolio which consist best firms in BIST.

My motivation to choose this project topic is that i personally use this two-step portfolio construction in my personal life. But this process takes at least 2-3 full-days to construct by using Ms Excel. Beside that, when relative stock price levels change, adaptation of my personal portfolio also takes at least 2-3 full-days too. I hope i can build my portfolios in minutes instead of days with this project. 
