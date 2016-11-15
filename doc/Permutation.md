Permutation:
Listing of all different arrangements of a list of items. Iterms can duplicate.
Elements of the same value is treated as the same.

Say there are n different elements:
First cell can choose from n values.
Second cell n-1 values (since 1 value is already taken)
...
n(n-1)(n-2)....1 == n!

If there are p elements of the same value, then
n!/p! 

Algorithm 1:
