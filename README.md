 Music App Smart Cache (LRU)

This project implements a `Music Smart Cache` using the Least Recently Used (LRU) eviction policy.  
It is built using:

-Doubly Linked List– to maintain the order of songs from Most Recently Used (MRU) to Least Recently Used (LRU)
-HashMap – to allow fast (O(1)) access to songs in the cache

This project follows the requirements of Problem 25: The Music App Smart Cache.

  Files in this Repository

- SongNode.java — Contains:
  - SongNode class (doubly linked list node)
  - MusicCache class (LRU cache implementation)

- MusicApp.java — Contains:
  - The main method
  - Command Line Interface (CLI) for interacting with the cache



Supported Commands

Once the program is running, you can use these commands:


1. INIT <n> Initialize the cache with capacity `n` 
2. PLAY <song> Play a song and update the cache 
3. SHOW_CACHE Display cache from MRU → LRU 
4. EXIT Close the program 


 How to Compile and Run

1. Open a terminal in the project folder and run the file MusicApp.java
2. type INIT 3 for example this will display something like Music cache initialized with capacity 3
3. then type any music you would like to add to the cache like PLAY Bohemian Rhapsody this will display something like Cache (MRU -> LRU): Bohemian Rhapsody
4. then continue to use the key word PLAY to add new songs until the max limit is reached 
5.when the limit is reached the CLI will display some thing like Evicting 'Bohemian Rhapsody' cause the cache is full and the LRU music will be removed 
6.once done use EXIT to stop the process.


