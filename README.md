**The Ravenous Bunny**
<br>
[ Memory: 16 MB, CPU: 1 sec ]

Brooke, an insatiable bunny, is always famished. Each day, she feasts on a carrot for dinner if there is one available in the barn. To ensure Brooke doesn't starve, The mailman occasionally arranges carrot deliveries in the morning before dinner. On day di
, The mailman sends a delivery of bi
 carrots (1≤di≤1014
, 1≤bi≤109
). Your task is to calculate the total number of carrots Brooke will devour during the first T
 days.

INPUT FORMAT

The first line consists of two integers, N
 and T
 (1≤N≤105
, 1≤T≤1014
), representing the number of delivery days and the total number of days, respectively.

The subsequent N
 lines contain two space-separated integers each: di
 and bi
. Furthermore, it is guaranteed that 1≤d1<d2<…<dN≤T
.

OUTPUT FORMAT

Output a single integer, indicating the total number of carrots that Brooke will consume during the first T
 days.

Note: Due to the large integers involved, you may need to employ a 64-bit integer data type (e.g., a "long long" in C/C++).

SAMPLE INPUT

    2 7 
    1 3 
    4 5
<br>
SAMPLE OUTPUT

    7
<br>
Brooke has 7 days to satisfy her insatiable hunger. On the morning of day 1, 3 carrots are delivered. Brooke consumes one carrot each day from day 1 to day 3. On the morning of day 4, 5 additional carrots are delivered. Brooke then eats one more carrot at dinner on days 4 through 7.
<br>
<br>
SCORING:
<br>
Inputs 4-7: T≤105<br>
Inputs 8-13: No additional constraints.<br>
<br>
MODE: normal<br>
Language: python3<br>
