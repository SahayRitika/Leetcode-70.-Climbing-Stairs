class Solution {
    public int climbStairs(int n) {
        int a=1,b=2,res=0;
        if(n==1 || n==2){
            return n;
        }
        for(int i=3;i<=n;i++){
            res=a+b;
            a=b;b=res;
        }
        return res;
    }
}
