class Solution(object):
    def twoSum(self, nums, t):
        n=len(nums)
        d={}
        for i in range(0,n):
            a=nums[i]
            b=t-a
            if(b in d):
                return(i,d[b])
            d[a]=i
