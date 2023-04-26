# binary_search

This is a simple C program that implements the binary search algorithm to search for a given number in a sorted array. The program takes an input number from the user and searches for it in the array using binary search, which has a time complexity of O(log n).

Algorithm:
1.Initialize variables:

    beg = 0 // starting index of the search range
    end = n - 1 // ending index of the search range
    result = -1 // initialize result to -1, assuming number not found
    
2.While beg <= end:

    a. Compute mid = (beg + end) / 2 // calculate the middle index of the search range
    b. If arr[mid] == target:
    - Set result = mid // number found, store index in result
    - Break out of the loop
    c. If arr[mid] > target:
    - Set end = mid - 1 // update the ending index of the search range to the left of mid
    d. If arr[mid] < target:
    - Set beg = mid + 1 // update the starting index of the search range to the right of mid

3.Print the result // print the index of the found number or -1 if not found

4.End

![image](https://user-images.githubusercontent.com/126075191/234511944-586dd6a5-0835-4659-85dd-323ba3688518.png)


Output :


![image](https://user-images.githubusercontent.com/126075191/234512334-651d843a-8710-4cbd-84c5-b2d35643200e.png)
