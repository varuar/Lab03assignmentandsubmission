# Lab03assignmentandsubmission
#Problem 1) Find and show how to compute Big O for the following algorithm: 70%:

The Big O for this algorithm is O(n^2). This is because the outer loop (while loop with iterate1) runs n-1 times, and for each iteration of the outer loop, 
the inner loop (while loop with iterate2) runs n times. Therefore, the total number of iterations is (n-1) * n = n^2. 
The operations within each iteration are constant time operations, so the overall time complexity is O(n^2).

#Problem 2) You have 20 M&M's bags. 19 bags have 1.0 gram pieces, but one has 1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bag? You can only use the scale once.  30% Please describe your solution using a MS Word document.

To find the heavy bag with only one use of the scale, we can use the following method:
Take 10 M&Ms from each of the 20 bags, for a total of 200 M&Ms.
Put the 200 M&Ms on the scale and weigh them.
If the weight is exactly 210 grams, then we know that the heavy bag does not contain any M&Ms that we weighed. If the weight is not exactly 210 grams, then we know that one of the bags we weighed is the heavy bag.
Next, we will determine which bag is the heavy bag:
Divide the weighted M&Ms into 10 equal piles of 20 M&Ms each.
Weigh each pile of 20 M&Ms.
The pile that weighs more than 2 grams is the pile containing M&Ms from the heavy bag.
We now have the heavy bag, and can weigh its individual M&Ms to determine which one is the heavy M&M.
By using this method, we are able to find the heavy bag with only one use of the scale, and with a maximum error of 0.05 grams per M&M.

