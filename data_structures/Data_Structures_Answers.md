For each of the methods associated with each data structure, classify it based on its runtime, using Big O notation.

## Linked List

1.  What is the runtime complexity of `addToTail`? 0(1)

a. What if our list implementation didn't have a reference to the tail of the list in its constructor? What would be the runtime of the `addToTail` method? 0(n)

2.  What is the runtime complexity of `removeHead`? 0(1)

3.  What is the runtime complexity of `contains`? 0(n)

4.  What is the runtime complexity of `getMax`? 0(n)

## Queue

1.  What is the runtime complexity of `enqueue`? 0(1)

2.  What is the runtime complexity of `dequeue`? 0(1)

3.  What is the runtime complexity of `isEmpty`? 0(1)

4.  What is the runtime complexity of `length`? 0(1)

## Doubly Linked List

1.  What is the runtime complexity of `ListNode.insertAfter`? 0(1)

2.  What is the runtime complexity of `ListNode.insertBefore`? 0(1)

3.  What is the runtime complexity of `ListNode.delete`? 0(1)

4.  What is the runtime complexity of `DoublyLinkedList.addToHead`? 0(1)

5.  What is the runtime complexity of `DoublyLinkedList.removeFromHead`? 0(1)

6.  What is the runtime complexity of `DoublyLinkedList.addToTail`? 0(1)

7.  What is the runtime complexity of `DoublyLinkedList.removeFromTail`? 0(1)

8.  What is the runtime complexity of `DoublyLinkedList.moveToFront`? 0(1)

9.  What is the runtime complexity of `DoublyLinkedList.moveToBack`? 0(1)

10. What is the runtime complexity of `DoublyLinkedList.delete`? 0(1)

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the `Array.splice` method. Which method generally performs better?

## Binary Search Tree

1.  What is the runtime complexity of `insert`?

2.  What is the runtime complexity of `contains`?

3.  What is the runtime complexity of `getMax`?

4.  What is the runtime complexity of `depthFirstForEach`?

5.  What is the runtime complexity of `breadthFirstForEach`?

6.  [Stretch Question] What is the runtime complexity of your `checkBalanced` function?

## Heap

1.  What is the runtime complexity of your `heapsort` function? 0(n)?

2.  What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array? 0(n); 0(1)

3.  What is the runtime complexity of `bubbleUp`?

4.  What is the runtime complexity of `siftDown`?

5.  What is the runtime complexity of `insert`?

6.  What is the runtime complexity of `delete`?

7.  What is the runtime complexity of `getMax`? 0(1)
