
Steps:

* Given an array of size n
* For each iteration compare each adjacent element if next element is smaller than current then do swap other wise continue;


## Time complexity and space complexity
* Time complexity would be ```O(N^2)```
* Space complexity would be ```O(1)```

```java
static void bubbleSort(int[] arr){
        int n = arr.length;
        for(int i =0; i<n-1 ; i++){
            for(int j = 0; j< n-i-1; j++){
                if(arr[j] > arr[j+1]){
                    swap( arr , j, j+1);
                }
            }
        }
        
        
    }
   ```
