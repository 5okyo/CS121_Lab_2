create an int with a constant value, MAX = 9, this value is the max length of the array  
prototype of printValues
prototype of sort
prototype of swap
all functions accessible in main


main():
    make array of int (given) , int values[] = {random numbers not in order}
    print the starting array to show the user the before
    
    swapping
    numbers put in x and y values to test if swapping works, specifically 3 and 5 
    print preswapped values
    swap, from the function created before main
    print postswapped values

    sort array
    print sorted array. showing the after result to user





function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array) 

function printValues (array):
    create integer variable i
    initalize i to 0
    for i < MAX, increment i: 
        printf(d (array + i))
    print ("\n")
        
function swap (x y):
    create a temporary integer and set it to x
    overwrite x with y
    overwrite y with temp 
     
    


