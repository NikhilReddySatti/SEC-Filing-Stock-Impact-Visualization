# SEC-Filing-Stock-Impact-Visualization

This repository has the code for the project which check's the hypothesis of the paper in Context.

Project Title: Impact of SEC Filing's Similarity Index for Consequent Years on Stock Prices of Tech Comapnies.

Hyothesis: The paper "The positive similarity of company fillings and the cross-section of stock returns" suggests that if the SEC Filings of consecutive years for a company are inversely proportional to the growth of stock value.

Companies Considered: Apple, Microsoft, Google, IBM, AMD, Meta, Amazon, Netflix

Years Considered For Study: 2018-2022

Software Used: Wolfram Mathematica

Approach: Using text analysis, each SEC filing was parsed and compared with it's consecutive years to create a similarity index. Additionally the financial data of each company is available on Wolfram Mathematica, the code plots each company's stock price for 1 week after SEC Filings and for 1 month after SEC Filings. Additionally to understand the true change of stock value, it has been subtracted by the net market value change as well for both 1 week and 1 month.
