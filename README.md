# array-min-max

int[] a={1,2,3,4,5,6,7,8,9,10};
   
       int  max=a[0];
        int m2=a[0];
        for(int i=0;i<a.length;i++)
        {
            if(max<a[i])
            {
                max=a[i];
       
            }
           
        }
    
        for(int i=0;i<a.length;i++)
        {
            if(m2<a[i] && m2!=max)
            {
               m2=a[i];
               
            }
        }
        System.out.println(m2);
