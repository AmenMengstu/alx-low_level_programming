
# 0x12-singly_linked_lists PROJECTS 
# Singly Linked Lists
This project contains C tasks for learning about singly linked lists.

Tasks Completed
 0. Print list
0-print_list.c contains a function that prints all the elements of a list_t list.
 1. List length
1-list_len.c contains a function that returns the number of elements in a linked list_t list.
 2. Add node
2-add_node.c contains a function that adds a new node at the beginning of a list_t list.
 3. Add node at the end
3-add_node_end.c contains a function that adds a new node at the end of a list_t list.
 4. Free list
4-free_list.c contains a function that frees a list_t list.
 5. The Hare and the Tortoise
100-first.c contains a function that prints You're beat! and yet, you must allow,\nI bore my house upon my back!\n before the main function is executed.
 6. Real programmers can write assembly code in any language
101-hello_holberton.asm is a 64-bit program in assembly that prints Hello, Holberton, followed by a new line.

# what are LinkedLists✔✔✔⁈⁈⁈😕😕😕
A linked list is a data structure where one object refers to the next one in a sequence by storing its address. Each object is referred to as a node. In addition to a reference to the next object in the sequence, each object carries some data (e.g., integer value, reference to string, etc.). The following diagram illustrates a typical linked lists:
![image](https://user-images.githubusercontent.com/99494058/164386228-b9010e82-8398-4061-a9cd-2e43d8ff0319.png)
![image](https://user-images.githubusercontent.com/99494058/164386379-3f5953d2-c12d-47f8-8e9e-47e4f1517827.png)
# A LinkedList Class
The following is a typical LinkedList class definition where the node class has been defined as an inner class. Although we are defining a linked list of strings, the example is representative of any linked list.
![image](https://user-images.githubusercontent.com/99494058/164386455-2787d27a-f410-40cf-a950-2a4945b0d205.png)
![image](https://user-images.githubusercontent.com/99494058/164386527-3b71a543-ce18-4805-8594-78e6d0d09a8b.png)
![image](https://user-images.githubusercontent.com/99494058/164386610-00be63f1-d5cb-4e4f-abdc-8256039d3ecc.png)
![image](https://user-images.githubusercontent.com/99494058/164386713-713e492a-8c86-47f7-a88d-20bd1af8488b.png)
![image](https://user-images.githubusercontent.com/99494058/164386785-99913952-2c21-416a-9543-41e2839b47dc.png)
# Recursion

Implementing recursive solutions to linked lists usually requires an auxiliary that will take a head reference as a parameter. For example, printing a list can define as follows:
![image](https://user-images.githubusercontent.com/99494058/164386944-83320270-b6e8-44b1-a096-48a9fdca6fd3.png)
A modification of the list using recursion is represented by the following example:
![image](https://user-images.githubusercontent.com/99494058/164387016-d24cc5ba-5f5b-4330-a227-371c2d80138c.png)
# Miscellaneous

Any insertion or removal operations must consider whether the head is affected. The dummy node strategy where the head points to a node that then refers to the first node in the list simplifies linked lists operations as the head never changes. The following represents a list that relies on the dummy node strategy.
![image](https://user-images.githubusercontent.com/99494058/164387108-f2209a41-1434-477b-9fd6-6825d214b61f.png)
1. Remember that the nodes of a list are kept in the heap.
2. We want to use a linked list when we are implementing a stack or a queue. Because linked lists keep track of the head, it is O(1) to insert or remove at the beginning of the list (e.g., stack). If the linked list is double-ended, it is O(1) to perform inserts/removes at both ends (e.g., queue, deque).
3. Arrays vs Linked Lists:
# Arrays

. Size: fixed
. Insert: expensive, since new space has to be created and existing elements have to be shifted.
. Access/indexing: O(1)
# Memory: elements are stored near each other.

# Linked Lists

1. Size: dynamic
2. Insert: cheap, just need to readjust pointers.
3. Access/indexing: O(N)
4.  Memory: elements could be stored far apart. Allocated at run-time. Extra memory required for pointers.
# Full Example
![image](https://user-images.githubusercontent.com/99494058/164387481-fc7a7957-fd20-481f-a060-0c99277bff31.png)
![image](https://user-images.githubusercontent.com/99494058/164387570-8ff78a24-d995-4351-8eda-f714f3fe32e4.png)
for further lecture see  https://www.youtube.com/watch?v=udapt4FGY20&t=130s
