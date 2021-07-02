# Heap-Sort-Optimization

Pseudo code for Heap Sort:
function heapsort(input, count)

heapify(a,count)
 end <- count - 1
 while end -> 0 do
 swap(a[end],a[0])
 end<-end-1
 restore(a, 0, end)
function heapify(a, count)
 start <- parent(count - 1)
 while start >= 0 do
 restore(a, start, count - 1)
 start <- start - 1
