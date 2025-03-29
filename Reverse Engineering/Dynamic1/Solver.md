![image](https://github.com/user-attachments/assets/9bdae592-20bc-44cf-9988-652f3fbcd5b4)

To solve this challenge, the user must:

Understand the Functions:

Analyze countWays, tribo, cha9an, and faza to determine their outputs for specific inputs.

Tribo : This function calculates the n-th Tribonacci number using memoization (a dynamic programming technique).

CountWays : This function calculates the number of ways to climb n stairs, where you can take either 1 step or 2 steps at a time.

It uses a recursive approach similar to the Fibonacci sequence.

Calculate the Required Values:

Compute faza("DolmaDessertDuckCouscousCakeC") to get "D21C".

How D21C :

faza() : return ch["0"]+len(ch)-CountWays(5)+ch[len -1 ]

Compute cha9an(10) to get "0011247132444".

Tribonacci number : 

i=0 --->res=0|| i=1 --->res+= 0 =00|| i=2 --->res+= 1 =001||i=3 --->res+= 1 =0011||i=4 --->res+= 2 =00112||i=5 --->res+= 4 =001124||i=5 --->res+= 4 =001124||i=6 --->res+= 7 =0011247||i=7 --->res+= 13 =001124713||
i=8 --->res+= 24 =00112471324||i=9 --->res+= 44 = 0011247132444

return res

Compute countWays(5) to get 8.

![image](https://github.com/user-attachments/assets/af649c60-34b3-429f-89fd-757715c00d21)

FLAG : Spark{D21C_0011247132444_8}

Resources :

https://www.geeksforgeeks.org/tribonacci-numbers/

https://www.geeksforgeeks.org/count-ways-reach-nth-stair/
