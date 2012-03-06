# Lock-free Data Structures in Java

Lock-free (non-blocking) stack and linked list implemented using compare and swap in Java. Lock-free data structures allow concurrent access to the structure without the use of mutex, semaphores or other kinds of thread synchronization. Lock free data structures allow higher level of concurrency because threads are not blocked.

For more information, check out my article at [IBM developerWorks](http://www.ibm.com/developerworks/cn/java/j-lo-lockfree/index.html).

## Lock-free Stack API

* `push(T value)` Push the given element to the stack
* `peek()` Return the top element in the stack
* `pop()` Remove the top element in the stack

## Lock-free Linked List API

* `addFirst(T value)` Prepend the element to the linked list
* `addAfter(T value)` Append the element to the linked list
* `remove(T value)` Remove the element in the linked list

## See Also

* [Lock-Free Data Structures](http://erdani.org/publications/cuj-2004-10.pdf?cm_mc_uid=83257434813514473321813&cm_mc_sid_50200000=1451401010)
* [A Pragmatic Implementation of Non-Blocking Linked-Lists](http://research.microsoft.com/~tharris/papers/2001-disc.pdf)
* [LockFree Linked Lists and Skip Lists](http://www.cse.yorku.ca/~ruppert/papers/lfll.pdf)
