# dijikstras_in_C
Coded dijikstras in C in order to resolve an issue in CSE102 Winter Quarter 2020

Had to code this algorithm because the instructor decided that my answer to a Dijikstra's Algorithm trace was a wonderful art project but it did not communicate the data structures in the way he wanted. My trace was very similar in style to multiple textbooks including the one he was given author credit for. There are bugs in this I am sure since I just threw it together as fast as possible and the error checking is not robust. Currently it stores a directed graph as an nxn (n is currently limited to 26 since I am using ascii conversion for vertex labeling) adjacency matrix and prints out an array of structs everytime the fringe is updated with a final printing of the finished run. '@' in the parent field represents no parent. Status is defined as an enum {tree, fringe, unseen}.  
