#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This is O(n) linear  because as input or "a" gets bigger, the runtime grows accordingly.


b) THis is Logarithmic O(log n ) because the sum grows at a slightly slower rate than the input "n". ( J increases exponentially so the growth rate of sum is limited to the value of J as it increase)


c)This is O(n) linear  because as input or "bunnies" gets bigger, the runtime grows accordingly.

## Exercise II

<!-- uppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution. -->

N equals the amount of stories in the building 
F equals the floor within N stories that eggs  to break 
C is the current floor being tested
M is the middle floor
we first divide N/2 then do the first test at M. If the egg doesnt break at the  M floor , we  know that the egg breaks at higher floors so we can eliminate testing on all the floors below M.  We then start testing each C floor above M until we find the F floor. If the egg did break at M , we know that F is  equal to M or the floors below it. We then start testing each floot below M until we find F . THis approach would be Logarithmic O(log n)


