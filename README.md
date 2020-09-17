# simple-lucky-draw
Prototype a lucky draw system.
Prototype the logic of a lucky system for members. It might be repacked into a Django app woth membership system once the logic is done.

Idea @2020-09-16.

## Initial Ideas
1. Use [faker](https://github.com/joke2k/faker) to generate member data.
2. Each member data as an object. (for interface programming in the future. 對接口編程。)
3. Lucky draw members by top k frequency. (loop and loop over for n times, then get the top k members for the prize)
