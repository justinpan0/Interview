# Interview


1. How to find a self-loop in linked list?

By iterating two pointers, one fast one slow, and if their is a loop, they will overlap.

2. How to concatenate two strings so that two strings remain distinguishable?

By write the first string twice for each char, and then insert a pair of different char between the two strings.

3. Is there a perfect compiler?

No, because otherwise it can find the shortest program, which is Turing undecidable; it also can find infinite loop, and replace it with one line, which is also Turing undecidable.

4. Introsort

If size is small, use insertion sort; if recursive depth deeper then 2*log(n), use heapsort; else use quicksort.
