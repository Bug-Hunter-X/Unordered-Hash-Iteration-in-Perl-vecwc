This example demonstrates an uncommon Perl bug related to the unordered iteration of hashes.  Perl's hash iteration order is not guaranteed to be consistent between runs or even within a single run if the hash is modified during iteration. This can lead to unexpected behavior if the order of elements matters in your application. The solution shows how to iterate using a sorted key list to ensure predictable order.