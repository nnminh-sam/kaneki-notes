# Two Sum

```java
import java.util.Map;

class Solution {
    public int[] twoSum(int[] nums, int target) {
        int numLength = nums.length;
        Map<Integer, Integer> numMap = new HashMap<>();
        for (int i = 0; i < numLength; ++i) {
            if (!numMap.containsKey(nums[i])) {
                numMap.put(nums[i], i);
            }
        }

        for (int i = 0; i < numLength; ++i) {
            if (numMap.containsKey(target - nums[i])) {
                int deductionIndex = numMap.get(target - nums[i]);
                if (deductionIndex != i) {
                    return new int[] {i, deductionIndex};
                }
            }
        }
        return new int[] {-1, -1};
    }
}
```