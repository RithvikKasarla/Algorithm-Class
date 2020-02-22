# Sorting Algorithms

## Selection Sort
    Step 1: Find the smalled element and swap it with the first element of your array

    Step 2: Find the second smallest element and swap that with the second element of your array

    * Do this until the array is sorted.

    Worst Runtime as it is always O( n^2 )

## Insertion Sort

    Take a number and insert it into the correct position in another array
    ex. 
        Array 1 = [1,5,6,3]
        Array 2 = []

        Step 1:
            Array 1 = [5,6,3]
            Array 2 = [1]
        
        Step 2:
            Array 1 = [6,3]
            Array 2 = [1,5]
            * Since 5 was greater than 1 it goes to the left of it

        Step 3:
            Array 1 = [3]
            Array 2 = [1,5,6]
            * Since 6 was greater than 1  and 5 it goes to the left of them    

        Step 4:
            Array 1 = []
            Array 2 = [1,3,5,6]
            * Since 3 was greater than 1  but less than 5 it goes between them                   

    Worst Case Runtime as it is always O( n^2  )

## Merge Sort
    A type of Divide and Conquer Algorithm

    Step 1:
        Divide your staring array(length n) into n lists with 1 element each

    Step 2:
        Recursively combine the lists back up again sorting them as you go.

    ex.
        Array = [1,2,8,7]
        Divided Part: [1], [2], [8],[7]
        First 2 combine into: [1,2] && second 2 combine to [7,8]
        Then combine [1,2] and [7,8] into [1,2,7,8]
    
    Worst Case Runtime as it is always O( n(log n) )
