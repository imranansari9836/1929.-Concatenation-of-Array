class Solution {
    public int[] getConcatenation(int[] nums) {
        int ans[]=new int[2*nums.length];//[1,2,1,1,2,1]
        for(int i=0;i<nums.length;i++)
        {
            ans[i]=nums[i];
            ans[i+nums.length]=nums[i];
        }
        return ans;//[1,2,1,1,2,1]
    }
}
