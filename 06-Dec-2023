class Solution {
    int countX(int L, int R, int X) {
        // code here
        int ans=0;
        for(int i=L+1;i<R;i++){
            int num=i;
            int count=0;
            while(num!=0){
                int temp=num%10;
                if(temp==X)count++;
                num/=10;
            }
            ans+=count;
        }
        return ans;
    }
};
