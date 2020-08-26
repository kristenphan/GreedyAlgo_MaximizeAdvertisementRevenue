# Greedy Algorithm: Maximize Advertisement Revenue
__Respository Description:__
This repo contains code written by myself, Kristen Phan, as part of a Coursera course (https://www.coursera.org/learn/algorithmic-toolbox). Please refrain from reading the script if you're currently taking the course. 
<br/>

__Problem Introduction__
You have 𝑛 ads to place on a popular Internet page. For each ad, you know how
much is the advertiser willing to pay for one click on this ad. You have set up 𝑛
slots on your page and estimated the expected number of clicks per day for each
slot. Now, your goal is to distribute the ads among the slots to maximize the
total revenue.
<br/>

__Problem Description__
Task. Given two sequences 𝑎1, 𝑎2, . . . , 𝑎𝑛 (𝑎𝑖 is the profit per click of the 𝑖-th ad) and 𝑏1, 𝑏2, . . . , 𝑏𝑛 (𝑏𝑖 is
the average number of clicks per day of the 𝑖-th slot), we need to partition them into 𝑛 pairs (𝑎𝑖, 𝑏𝑗)
such that the sum of their products is maximized.
Input Format. The first line contains an integer 𝑛, the second one contains a sequence of integers
𝑎1, 𝑎2, . . . , 𝑎𝑛, the third one contains a sequence of integers 𝑏1, 𝑏2, . . . , 𝑏𝑛.
<br/>

__Constraints.__
1 ≤ 𝑛 ≤ 103; −105 ≤ 𝑎𝑖, 𝑏𝑖 ≤ 105 for all 1 ≤ 𝑖 ≤ 𝑛.
<br/>

__Output Format.__
Output the maximum value of
Σ︀𝑛
𝑖=1
𝑎𝑖𝑐𝑖, where 𝑐1, 𝑐2, . . . , 𝑐𝑛 is a permutation of
𝑏1, 𝑏2, . . . , 𝑏𝑛.
<br/>

__Sample 1.__
Input:
<br/>
1
<br/>
23
<br/>
39
<br/>
Output:
<br/>
897
<br/>
897 = 23 · 39.
