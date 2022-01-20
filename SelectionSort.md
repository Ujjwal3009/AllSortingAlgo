
## Problem link -> https://practice.geeksforgeeks.org/problems/selection-sort/1/


Steps:

* Given an array of size n
* Select an element and then chck for its correct position .


## Time complexity and space complexity
* Time complexity would be ```O(N^2)```
* Space complexity would be ```O(1)```

```java
	void selectionSort(int arr[], int n)
	{
	    //code here
	    for(int i = 0; i< n-1; i++){
	        int min_idx = i;
	        for(int j = i+1; j< n; j++){
	            if(arr[j] < arr[min_idx]) min_idx = j;
	        }
	        int temp = arr[i];
	        arr[i] = arr[min_idx];
	        arr[min_idx] = temp;
	    }
	}
    
    
    
   ```
   
