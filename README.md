# Hash-Map-Open-Addressing

This is an implementation of a hash map data structure that uses open addressing for collisions. This implementation utilizes a basic dynamic array that resizes when the table load is >= 0.5. All key value pairs within the original table are rehashed before continuing with the addition of the new entry. This hash map uses quadratic probing to find open indexes within the array if a hashed index is already taken.

The hash_map_oa.py file has tests built in, just run the file in a terminal to see the results!

NOTE: File will not run without the a6_include.py file.
