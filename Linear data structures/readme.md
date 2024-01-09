## Difference Between Linked List and Array:
Linked list and Array both are linear data structures used for storing collection of elements. Here are differences between them, on the basis of these differences, we use them in difference situations:
- **Memory Allocation:**
    - **Linked List:** Elements are stored in nodes that may be scattered in different locations in memory. We can traverse(print) them by using 'next' part of nodes, that contains address of next node.
    - **Array:** Elements are stored at continous memory locations. We can access them directly through indexing.
- **Size:**
    - **Linked List:** Adding and Removing elements become easy.
    - **Array:** Adding and Removing elements may takes longer time than linked list. Because it shift elements from one position to another after inserting or removing elements.
- **Access Time:**
    - **Linked List:** Requires O(n) time to access elements, because it needs to move from start of node(which is head) till end(tail).
    - **Array:** Requires O(1) time to access elements.
- **Traversal:**
    - **Linked List:** Typically traversed in a sequence from beginning to end.
    - **Array:** Allow random access, we can traversed them in any order.

**Note:**
- If you work on software that's provide mostly functionality on Inserting and Removing, then use Linked List. It's will work fast than Array.
- If you work on software that's provide mostly functionality on Accessing items, then use Array. It will work fast than Linked List.
