#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
You start with n^2; you need n more n's to get to n^3

b) O(n^2)
for loop = O(n)
nested while loop = O(n/2) ≈ O(n)
multiply them because they're nested
O(n) * O(n) = O(n^2)

c) O(n)
There is only 1 operation per ear

## Exercise II

O(logn)
egg_drop_soup(n, f, l, r):
  while l <= r:
    m = l+(r-1)//2
    if n[m] == 'cracked': l = mid+1
    else: r = mid-1
  return l