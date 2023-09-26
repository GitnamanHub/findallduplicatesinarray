class Solution {
public:
    vector<int> findDuplicates(vector<int>& nums) {
        sort(nums.begin(),nums.end());
        int n=nums.size();
        vector<int> duplicates;
        for(int i=0;i<n-1;i++)
        {
            if(nums.at(i)==nums.at(i+1))
            {
                duplicates.push_back(nums.at(i));
                i++;
            }
            
        }

        return duplicates;
    }
};
