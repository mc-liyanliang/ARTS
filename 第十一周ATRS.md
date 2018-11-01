LeetCode
====
algorithm
----
###review<br>
* 哈哈<br>
* 哈哈
* 哈哈<br>
#本周的<br>
  `不管`怎么样
学习的重点是<br>
---
啊哈<br>
[我的博客](https://blog.csdn.net/guodongxiaren/article/details/23690801)<br>
https://blog.csdn.net/guodongxiaren/article/details/23690801
```Cpp
    cout<<"Test for more ordered random array, size = "<<n<<", random range [0, 3]"<<endl;
    arr1 = SortTestHelper::generateRandomArray(n,0,3);
    arr2 = SortTestHelper::copyIntArray(arr1, n);

    SortTestHelper::testSort("Insertion Sort", insertionSort,arr1,n);
    SortTestHelper::testSort("Selection Sort", selectionSort,arr2,n);

    delete[] arr1;
    delete[] arr2;

    cout<<endl;
    ```
