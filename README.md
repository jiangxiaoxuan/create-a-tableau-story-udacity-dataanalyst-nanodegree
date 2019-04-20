# create-a-tableau-story-udacity-dataanalyst-nanodegree

Created a tableau story to provide suggestions for lenders in peer-to-peer loan platform. Data for analysis and relevant definitions are included in this GitHub Repo.

<img src="https://github.com/jiangxiaoxuan/create-a-tableau-story-udacity-dataanalyst-nanodegree/raw/master/prosper-logo.png" width = 300 />

[First Version of My Tableau Story](https://public.tableau.com/profile/xiaoxuan.jiang#!/vizhome/UdacityNanodegreeProsperLoansAnlaysis/Story1?publish=yes)

[Final Version of My Tableau Story](https://public.tableau.com/profile/xiaoxuan.jiang#!/vizhome/ProsperLoansAnalysisaguideforlenders/Story1?publish=yes)

# Preview of Tableau Story

<img src="https://github.com/jiangxiaoxuan/create-a-tableau-story-udacity-dataanalyst-nanodegree/raw/master/preview.png"/>

# Summary

This is for people who want to lend their money and gives information on a lending market. Loan data information from Prosper, a lending platform, contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Important information for lenders in visualized. 

# Design
* I explore the data from the lender’s perspective and what they might be interested in knowing about the market.
 						
* I started from a broad view of a lending platform (Proper) over the years, one line graph showing that the number of loans, especially the higher rating loans have increased significantly and another bar chart that shows that the number of default, low quality loans has been kept low though the loan activities become much more. However, the completed loans decreased a bit with a drastic increase in current loan. This could be explained by increase in lender’s confidence and willingness to lend out longer term loans in the following graph of Term VS Year
 						
* The above analysis is to prove that the prosper loan market is worth investing in. The following graphs are meant for analysis of who, where and how to lend and invest in the peer-to-peer market.
 						
* So of course, first I would like to know the relationship between different ratings and the lender’s yield and loss. The conclusion is obvious, the higher the yield of the loan, the more risk the loan is.
 						
* Similarly, I explored the relationship between employment status, the yield and the loss. The higher the income, the lower the risk and the lower the yield.

* However, across the income group, the default loans tends to have a higher amount than the completed loans (7th graph). It shows that no matter how rich the group of people is, the more money they borrow, the higher the risk of going default.
After knowing about who and how to lend the money. Lastly, we had a look at the geographical loan data. The analysis has shown that the east and west coast area has higher peer-to-peer loan activities than middle US. Moreover, the east coast where most financial services located, the term of the loan tends to be longer than other areas.

* I put a very intuitive graph of packed bubbles to show that really the credibility of the borrowers and quality of loans is good now with most of the loans at completed and current status and small amount of loans going default.

# Feedbacks and Improvement


1. When clicking the publish-to-public button, one need to select out the first page of the story or else the published story will be showing to audience whatever page you are reading at the time you publish the story.
2. The line graph(1st graph) for prosper loans overview over the years has too many lines and the data in the 2014 should be taken off as it appeared to be a drop in the trend but actually it’s just because the data collection in 2014 was incomplete.
3. In the 2nd graph, one of my friends has noted that the completed loans had decreased, though the default loans kept low. This might be explained by the longer terms of the loans because people have more confidence in borrower’s credibility. An improvement will be inserting a graph(3rd graph) to illustrate the relationship of term VS year.
4. The scales of the 5th graph for average estimated lender yield and average estimated loss are different. So I later forced a scale of 0-0.34 on both scales to ensure consistency.
5. The AA and A rating rows should switch their positions so that the order of layout is consistently from highest rating to lowest rating.
6. Didn’t illustrate the average term information encoded in the colour information in the overview of geographical loan data(8th graph), The east bay of United States has been providing longer term of loans. So I added the explanation in the story text section of that graph.
7. We can see from the above comments that indexing the graphs is important for future references, so I added index for each graph such as "1st graph", "2nd graph",etc.

# Resources

Github Repo:
* https://github.com/igorstojanovic91/udacity-create-a-tableau-story
* https://github.com/latinacode/Create-a-Tableau-Story

Tableau Published Story:
* https://public.tableau.com/profile/steve7an#!/vizhome/prosper_loan_data_0/Story1


