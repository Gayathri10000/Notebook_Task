Node and LinkedList Classes:
1) Think of a node like a container. Each node can hold some information (data), and it knows where the next container is by using its reference.
2) The linked list is like a chain of these containers. You start with one container (the head), and each container knows where the next one is by the reference the next one, forming a chain.

DoubleNode and DoubleLinkedList Classes:
Similar to the single linked list, but there is small change is that each node now is like a two-way chain.

Notepad Class:
This class represents a notepad application.
It uses a DoubleLinkedList to store documents, where each document is represented by a LinkedList.
Methods like create_document, open_document, save_document, edit_document, navigate_document, search_document, and copy_paste provide functionalities like creating, opening, editing, navigating, searching, and copying documents.

Main Function:
The main function is the entry point of the program.
It creates a Notepad instance and runs a loop to interact with the user.
Based on the user's input, it calls the respective methods of the Notepad class to perform actions like creating, opening, editing, etc., documents.
