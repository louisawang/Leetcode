Leetcode
========
class Solution:
    # @return a tuple, (index1, index2)
    def twoSum(self, num, target):
        index1= 1
        n=len(self.num)
        index2= n
        is_found==0
        remainer=0
        for i in range (n):
            remainer=self.target-self.number[i-1]
            for j in range(i, n):
                if self.number[j]==remainer:
                    is_found =1
                    index1 = i
                    index2 = j+1
                    break
        return (index1, index2)
                    
                
