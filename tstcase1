class Solution {
    public static int findMoves(int n, int[] chairs, int[] passengers) {
        // code here
        //sorting chairs and passengers in ascending order
        Arrays.sort(chairs);
        Arrays.sort(passengers);
        
        //to keep track of moves
        int moves=0;
        
        
          for(int i=0;i<chairs.length;i++){
            while(chairs[i]!=passengers[i]){
                if(chairs[i]<passengers[i])
                passengers[i]--;
                else passengers[i]++;
                 moves++;
    }
  
}
  return moves;
}
}
