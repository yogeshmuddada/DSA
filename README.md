# DSA 
1. **Reverse of an array**
   ```
   Maintain two pointers(left and right) 
   While the left is less than the right, swap the left with the right, increment the left, and decrement the right.
   ```
   ```
   Replace the first element with the respective position element from the other end
   like 0th index element replace with n-1
        1th index element replace with n-1-1
        2th index element replace with n-2-1
        3rd index element replace with n-3-1
         .
         .
       i th index element replace with n-i-1
   ```

2. **Reverse of a string**
   ```
      with the above logic, we can solve the reverse of a string, but the problem is
      In Java strings are immutable so first we need to convert the char array then apply the above logic
      and finally again need to convert the char array to string.
   ```
