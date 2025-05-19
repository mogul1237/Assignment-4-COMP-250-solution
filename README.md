# Assignment-4-COMP-250-solution

Download Here: [Assignment 4 COMP 250 solution](https://jarviscodinghub.com/assignment/assignment-4-comp-250-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Hash Table
In this Assignment you will implement a hash table as an arraylist of buckets. Each bucket of the hash table contains a singly linked list of nodes containing key-value pairs.
The starter code consists of ﬁve classes: • MyHashTable which is a simpliﬁed and reduced version of HashMap • HashNode which stores a key-value pair (i.e. hash table entry); you may add helper methods to this class if you wish. For simplicity of editing, this is a separate java ﬁle rather than an inner class of MyHashTable. • HashLinkedList which is a linked list of HashNode objects with code stubs. • Song that describes song objects which will be stored in the hash table • HashTableTester class which uses a MyHashTable to store a list of songs. The key is the song title and the Song object is value. Thus, the key happens also to be one of the ﬁelds of value object.
You may add additional tests in the HashTableTester class, but you must not modify the Song class.
last updated: 22nd Nov, 2017 at 13:38 1
Your Task
(30 points)
Implement HashLinkedList, which is a simple version of the singly linked list class for the buckets of the hash table. You can start from the linked list implementation provided on the course web site ( Exercises 3) as a guide. In particular, implement the methods • add(K,V), remove(K), removeFirst(), getListNode(K). Note that you will need to modify the given singly linked list code to use it in your hash table. In particular, the HashLinkedList
