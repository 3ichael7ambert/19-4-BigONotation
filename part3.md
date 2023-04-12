## **Part 3 - short answer**

Answer the following questions

1. True or false: n^2 + n is O(n^2).
    Answer: True


2. True or false: n^2 * n is O(n^3).
    Answer: True


3. True or false: n^2 + n is O(n).
    Answer: False


4. What’s the time complexity of the .indexOf array method?
    Answer: O(n)
    because it will basically be looping through n.length looking for the indexOf


5. What’s the time complexity of the .includes array method?
    Answer: O(n)
    Due to same reason as #4

6. What’s the time complexity of the .forEach array method?
    Answer: O(n)
    Due to same reason as #4


7. What’s the time complexity of the .sort array method?
    Answer: I was not sure
    Solution: O(n log n)


8. What’s the time complexity of the .unshift array method?
    Answer: <!--O(1)-->
    Solution: O(n)
    This is because the method adds an element to the beginning of the array and shifts all the existing elements.

9. What’s the time complexity of the .push array method?
    Answer: <!--O(n)-->
    Solution O(1)
    it is O(1) and not O(n) due to the fact nothing shifts in an array
    
10. What’s the time complexity of the .splice array method?
    Answer: <!--O(n^n)-->
    O(n)
        n is the legnth of the array

11. What’s the time complexity of the .pop array method?
    Answer: O(1)
    due to the fact nothing shifts in an array


12. What’s the time complexity of the Object.keys() function?
    Answer: I was not sure at first
    Solution: O(n)
    n represents the number of keys




### **BONUS**

1. What’s the space complexity of the Object.keys() function?
