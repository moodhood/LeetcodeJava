import java.util.Set;
import java.util.HashSet;

public class Solution {
    public boolean containsDuplicate(int[] nums)  {
        Set<Integer> mySet = new HashSet<>();
        for(int num : nums){
            if(mySet.contains(num)){
                return true;
            }
            mySet.add(num);
            
        }
        return false;
    }
}

