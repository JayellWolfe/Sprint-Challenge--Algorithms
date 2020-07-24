#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The while loop executes until a is greater than or equal to n cubed, however n squared is added to it each iteration and so the loop will only run n times --  O(n) 


b) The first of the two loops is a for loop in the range of n which will execute in O(n) time. The second loop is a while loop which is constantly
j for every time it iterates, and it will execute in O(log (n)) time which leaves O(n) * O(log(n)) time 


c) This function is recursive, however it only calls iteself once, which leaves it in linear time 

## Exercise II

# Egg Case
# Starting on the ground  floor
# Find the middle floor between the start point and the top floor (n)
# run until floor f:
    # drop the egg
    # if the egg breaks:
        # move to the middle point between current location and the ground
    # otherwise:
        # move to the middle point between current location and the top floor
# return floor f
# floor f is the highest floor where the egg doesn't break

#giving a O(log(n)) time 
