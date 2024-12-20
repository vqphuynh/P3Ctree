Partial Pre-Post Code Tree: A Memory-Efficient Tree Structure for Conjunctive Rule Mining. P3Ctree (Partial Pre-Post Code Tree) significantly saves memory compared with PPC-tree. Both tree structures generate the same N-list structure for a dataset 
however P3Ctree can practically run faster than PPCtree for generating the basic N-lists (N-lists of single items) thanks to less cost of heap memory management.
N-list of an arbitrary k-itemset (k>1) can be generated efficiently from the basic N-lists. N-list of an itemset contains the support count of the itemset. 
Besides the original application for Frequent Itemsets Mining, N-list structure can be leveraged for any other purposes in which the support count of sets of feature values is queried with a very high frequency.

