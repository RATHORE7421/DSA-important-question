# Backtracking:
- used when u want to find multiple soltion of given problem under certain constraints.
- Backtracking is an algorithmic-technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions 
           that fail to satisfy the constraints of the problem at any point of time (by time, here, is referred to the time elapsed till reaching any level of the search
           tree)
- Based upon brute force approach
          
          
## Imporatnts:
1) N - queen tree:
    Pattern :Matrix 
             No. of eemtn equal to rows of matrix
             certain constraints
    BF: iterate through row or column 
        Check constraints: if true(check constraints in three dimentsion i.e left col , upper diagonal , lower diagonal ): call recursion over other dimension & backtrack
                           else if false continure
        when iterative variable is equal to diment=sion push in ans vector             
   Optimization : Use Hashing
                  make three vector i.e left col(n , 0) , upper diagonal(2n-1 , 0) , lower diagonal(2n-1, 0)
                  if places in given vctor==0 means queen is not under attack & therefore u can move further (leftr[row] , UD[n-1 + col-row] , LD[row+col]) 
                  make them 1 , call resursion , backtrack
                  
2) rat in a maze:
     Pattern :
3) Palindrome partitioning problem 
     Pattern : n*2^n
4) Print all possible permutations :
     Pattern : - All elements are to become first element .
               - Keep storing & mark it in the map.
               - Once size is equal to given array push into output array
               - Backtrack (Keep clearing last element & unmark the poping elements)
     ###### TC : O(n!*n)
     ###### SC : O(n!)(nut using map , vector)
