# What-s-In-a-Name-CS32-Project-4-
This project focuses on the concept of shadowing, where identifiers in an inner scope are hidden from those in outer scopes. I wrote code to keep track of declarations, allow for the entering and exiting of scopes, and find the most recent line number of an identifier available to us. In order to optimize searches and insertions, I implemented a hash table with minimized collisions and most recent identifiers at the top of each bucket (so they are easily searchable). I performed Big-O analysis to use the most time-efficient algorithms. main.cpp and generateTests.cpp are for the purpose of testing both functionality and efficiency.

See the report document for a more detailed description and pseudocode.
