#H1 DAA-Practical-2021
##H2Question -1
###H3omplexity:
The time-complexity of inserting a single element into an RB-tree is O (log n) where n is the current size of the tree. The time-complexity of inserting n elements into an empty RB-tree is, therefore, O (n log n). The time-complexity of inserting 10 elements into an empty RB-tree is constant, or O (1)
Applications:
Red-black trees are needed when height balancing is a desirable trait, and insertion/deletion must not be too slow either. RB trees are common in the Linux kernel. Two of the places where you can see it are:

In the Completely Fair Scheduler implementation - the process virtual runtimes serve as the key.
To keep track of the virtual memory segments for a process - the start address of the range serves as the key.
As you may notice, in both cases it is important to retrieve the node by their key rather quickly from performance considerations.
Question-02
Complexity:
Sorting of edges takes O(ELogE) time. After sorting, we iterate through all edges and apply the find-union algorithm. The find and union operations can take at most O(LogV) time. So overall complexity is O(ELogE + ELogV) time. The value of E can be at most O(V2), so O(LogV) is O(LogE) the same. Therefore, the overall time complexity is O(ElogE) or O(ElogV)
Applications:
-Cluster analysis
-Image segmentation
-Handwriting recognition
-Medical Image Processing
-Identify patterns in gene expression
Question-03
Complexity:

Application:
The library has a database that every computer can read from and only the librarian has access to be able to modify the values. This database stores all the information previously made available and adds another value, whether or not the book is available or someone else has it in their possession.

You can now go to the computer and type in the name of the book, the computer will look through the database to find the book in question and then will sort according to whether the book is in stock or not, the location of where it is and how many are available.
