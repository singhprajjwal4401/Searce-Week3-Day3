# Searce-Week3-Day3
Assignment and practice problems of day 3

#Daily Challenge Question:
Ramu owns a Pan shop and he manages it in his own way. While in a normal shop, a customer is served by following the first-come, first-served rule, Ramu simply minimizes the average waiting time of his customers. So he gets to decide who is served first, regardless of how sooner or later a person comes.

Different kinds of Pans take different amounts of time to cook. Also, once he starts cooking a Pan, he cannot cook another Pan until the first Pan is completely cooked. Let's say we have three customers who come at time t=0, t=1, & t=2 respectively, and the time needed to cook their Pans is 3, 9, & 6 respectively. If Ramu applies first-come, first-served rule, then the waiting time of three customers is 3, 11, & 16 respectively. The average waiting time in this case is (3 + 11 + 16) / 3 = 10. This is not an optimized solution. After serving the first customer at time t=3, Ramu can choose to serve the third customer. In that case, the waiting time will be 3, 7, & 17 respectively. Hence the average waiting time is (3 + 7 + 17) / 3 = 9.

Help Ramu achieve the minimum average waiting time. For the sake of simplicity, just find the integer part of the minimum average waiting time.

   #Input Format
   1.The first line contains an integer N, which is the number of customers.
   2.In the next N lines, the ith line contains two space separated numbers Ti and Li. Ti is the time when ith customer order a pan and Li is the time required to cook that pan.
   3.The  ith customer is not the customer arriving at the  ith arrival time. 

   #Output Format
   Display the integer part of the minimum average waiting time.
