# MS-Apriori-Algorithm
Algorithm is complete, just not pushed via Github. I wanted to optimize it and clean it up before posting it. =)

Apriori is a Data Mining Algorithm for frequent item set using association rules that learns over transactional databases. 
It proceeds by identifying the frequent individual items in the database and extends them to larger item sets as long as
the items appear in the database often. (With certain rules/constraints to define "often").
MS-Apriori is a modified version of Apriori, but instead it uses multiple supports to satisfy the conditions extending them to larger item sets.

Is MS Apriori better? Yes! It accounts for the "rare item support." Apriori only holds 1 minimum support for the entire transaction database.
In MS Apriori, we have multiple supports; every item has a min-support. This will improve the effectiveness of the association rules and account
for the rare items.


