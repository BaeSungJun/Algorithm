# Six Steps
> ## Problem: [Hansu 1065](https://www.acmicpc.net/problem/1065)
>
> ### 1. Understanding problem
> Hansu is a number which digits are arithmetic sequence. Find number of hansu which is same or less than number. 
> ### 2. Redefining a problem
> Find number of hansu which is same or less than N for given N. (1 <= N <= 1000)
> ### 3. Making a plan
> We are going to use brute force.
> We are going to find digits of number from 1 to N.
> If digits are arithmetic sequence, then we can add number of hansu by 1.
> ### 4. Validate a plan
> Time complexity is O(N ^ 3), since N is less than 1000, we have enough time to calculate.
> ### 5. Implement
> Here is my first code using brute force.  
> [code](https://github.com/DevStevenLee/Algorithm/blob/master/Brute_Force/Hansu_1065/Hansu_1065_kyongkyong289.py)
> (kyongkyong289, Version #1, 2019-01-09)
> ### 6. How it can be improved
>  I would like to recommend reducing the number of calling function to improve your code. actually, you called unnecessary functi
> on a few times. i think you need to save the result of digits(n) function u made in a value. reuse it over and over again. also,
> why don't you consider i < 100 case independently. just return out + 99 in number\_of\_hansu(n) :D <br />
>                                                       by Steven, Lee (2020-01-10. 10.53 pm)
>

