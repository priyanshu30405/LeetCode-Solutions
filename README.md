# LeetCode-Solutions
class Solution {
    public int[] getConcatenation(int[] nums) {
     int n = 2*nums.length;
        int result[]=new int[n];
        int j=nums.length;
        for(int i=0;i<nums.length;i++){ 
            result[i]=nums[i];
            result[j]=nums[i];
            j++; 
        }
        
        return result;
    }
}
