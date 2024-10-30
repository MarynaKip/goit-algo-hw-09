# goit-algo-hw-09

For small and standard denominations (like those used in US currency), both find_coins_greedy and find_min_coins provide optimal solutions efficiently. However, for large sums or unusual coin denominations, find_min_coins is guaranteed to yield the minimum coin count, though it may require more time and memory due to its dynamic programming approach.

The greedy algorithm is typically faster and more memory-efficient but may fail to find the minimal solution for certain sets of coin denominations. In cash register systems where denominations are fixed, find_coins_greedy is often preferred due to its speed.