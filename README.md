# sydhnshdef  countSetBits(n): 
    count = 0
    while (n): 
        count += n & 1
        n >>= 1
    return count 
  
  
# Program to test function countSetBits */ 
i = 7

print(countSetBits(i)) 
