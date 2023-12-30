class Solution
{
    //Function to return the name of candidate that received maximum votes.
    public static String[] winner(String arr[], int n)
    {
        // add your code
        String ans[] = new String[2];
        HashMap<String,Integer> map = new HashMap<>();
        for(int i = 0; i < n ; i++){
            map.put(arr[i],map.getOrDefault(arr[i],0)+1);
        }
        int max = Integer.MIN_VALUE;
        for(String s : map.keySet()){
            if(map.get(s) > max){
                ans[0] = s;
                ans[1]= String.valueOf(map.get(s));
                max = map.get(s);
            }else if(map.get(s) == max){
                if(ans[0].compareTo(s) > 0){
                    ans[0] = s;
                    ans[1] =String.valueOf(map.get(s));
                    max = map.get(s);
                }
            }
        }
        return ans;
    }
}
