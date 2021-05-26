# Stacks and Queues

* **Stack**: A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

### Common terminology for a stack is

1. Push - Nodes or items that are put into the stack are pushed
1. Pop - Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.
1. Top - This is the top of the stack.
1. Peek - When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.
1. IsEmpty - returns true when stack is empty otherwise returns false.

* **FILO-(First In Last Out):** This means that the first item added in the stack will be the last item popped out of the stack.

* **LIFO-(Last In First Out):** This means that the last item added to the stack will be the first item popped out of the stack.

### Push O(1)

1. First, you should have the Node that you want to add. Here is an example of a Node that we want to add to the stack.
1. Next, you need to assign the next property of Node 5 to reference the same Node that top is referencing: Node 4
1. Technically at this point, your new Node is added to your stack, but there is no indication that it is the first Node in the stack. To make this happen, you have to re-assign our reference top to the newly added Node, Node 5.
1. Congratulations! You completed a successful push of Node 5 onto the stack.

### Pop O(1)

1. The first step of removing Node 5 from the stack is to create a reference named temp that points to the same Node that top points to.
1. Once you have created the new reference type, you now need to re-assign top to the value that the next property is referencing. In our visual, we can see that the next property is pointing to Node 4. We will re-assign top to be Node 4.
1. We can now remove Node 5 safely without it affecting the rest of the stack. Before we do that though you may want to make sure that you clear out the next property in your current temp reference. This will ensure that no further references to Node 4 are floating around the heap. This will allow our garbage collector to cleanly and safely dispose of the Nodes correctly.
1. Finally, we return the value of the temp Node that was just popped off.
 
* **Queue**

Common terminology for a queue is

1. Enqueue - Nodes or items that are added to the queue.
1. Dequeue - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
1. Front - This is the front/first Node of the queue.
1. Rear - This is the rear/last Node of the queue.
1. Peek - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
1. IsEmpty - returns true when queue is empty otherwise returns false.
