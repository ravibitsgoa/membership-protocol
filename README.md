# membership-protocol
A solution to membership protocol assignment for cloud computing concepts part 1 (Coursera)

The protocol satisfies:
1) Completeness : 
  Every none faulty process detects every node join, failure and leave.
2) Accuracy of failure detection :
  When there are no message losses and message delays are small, all failures are detected.
  When there are message losses, completeness is satisfied and accuracy is high.
Here, SWIM style membership protocol is implemented.
