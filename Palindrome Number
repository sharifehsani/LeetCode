/*
  this is a LeetCode challenge
  Two Sum -LeetCode problem
  https://leetcode.com/problems/two-sum/
  Attempted - passed all the test cases
  Full solution
  
  Given an array of integers nums and an integer target, return indices of the
  two numbers such that they add up to target. You may assume that each input would have exactly one solution,
  and you may not use the same element twice.

  You can return the answer in any order.
  Example 1:

  Input: nums = [2,7,11,15], target = 9
  Output: [0,1]
  Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

  Example 2:

  Input: nums = [3,2,4], target = 6
  Output: [1,2]

  Example 3:

  Input: nums = [3,3], target = 6
  Output: [0,1]

*/
class Main {
  public static void main(String[] args) 
  {
    // create instance of the class
    Solution s = new Solution();
    int result[] = new int[2];
    result = s.twoSum(new int[]{-2,20,4,1}, 2);
    System.out.println("result 0 = " + result[0]);
    System.out.println("result 1 = " + result[1]);
    
  }
}

class Solution 
{
    public int[] twoSum(int[] nums, int target) 
  {

    // create an array of two elements to holds the matching indecis that hold the two numbers equaling the target 
    int result[] = new int[2];
    
    // loop through the input array and match the sum of thos indices that equals to target
    // if the sum is equal to target, return the indices
    // in these outer loop we check each index from left with each index on the right in the inner loop so that we can skip repeated checsk
    for(int i = 0; i < nums.length; i++)
      {
        for(int j = nums.length; j > i + 1; j--)
          {
           
            if(nums[i] + nums[j-1] == target)
            {
              System.out.println("Num one: " + nums[i]);
              System.out.println("Num two: " + nums[j-1]);
              System.out.println("Target: " + target);
              result[0] = i;
              result[1] = (j-1);
              
            }
          }
      }
    return result;

  }
}
