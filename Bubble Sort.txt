 public static void main(String[] args) {
       int a;
       int b;
       int t;
       int size=5;
       int nums[]={3,4,2,5,8};
       for(a=1; a<size; a++)
       {
           for(b=size-1; b>=a; b--)
           {
               if(nums[b-1] > nums[b]){
                  
                   t=nums[b-1];
                   t=nums[b-1] = nums[b];
       nums[b]=t;
                           
    }
           }
       }
           for(int i=0; i<5;i++)
           {
               System.out.println(nums[i]);
           }
               
           
       }
    }