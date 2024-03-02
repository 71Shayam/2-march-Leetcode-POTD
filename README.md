 vector<int> sortedSquares(vector<int>& nums) {
        vector<int>ans ;
        int i;
        for(int i=0 ; i<nums.size(); i++){
            ans.push_back(nums[i]*nums[i]) ;
        }
        if(nums[i]==-nums[i]){
            nums[i]+=2*nums[i] ;
        }
        sort(ans.begin(), ans.end()) ;
        return ans ;
    }
