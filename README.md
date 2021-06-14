# Bitcoin Mining Strategy

The idea here is to avoid computing costly computations of Knapsack Problem with relations between entities and resort to much quicker method (read: hack) which uses a greedy algorithm on the basis of density of transactions (the ratio of Txn fee and Txn size) where Txn size is the proportion of the weight of Txn to the maximum allowed total block weight.