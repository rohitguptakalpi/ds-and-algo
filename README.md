# ds-and-algo




Given an array which consists of only 0, 1 and 2. Sort the array without using any sorting algo [vvimp]

ans:
        low=0
        mid=0
        high=n-1
        
        while mid<=h:
            
            if arr[m]==0:
                arr[l],arr[m]=arr[m],arr[l]
                m+=1
                l+=1
            elif arr[m]==1:
                m+=1
            else:
                arr[m],arr[h]=arr[h],arr[m]
                h-=1
                
Move all the negative elements to one side of the array 

      j=n-1

      for i in range(n,):
        if arr[i]<0:
          arr[i],arr[j]==arr[i],arr[j]
          j-=1
      
