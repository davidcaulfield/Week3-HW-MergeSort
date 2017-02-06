#Merge Sort
Merge sort is a sorting technique based on divide and conquer. It starts by dividing a list of data into two equal sections and then follows this pattern until it gets down to individual numbers. It then sorts the list of 2 values and combines the lists that are next to each other and follows this pattern until the entire list is sorted.


```python
def mergeSort(alist):
	print("Splitting ",alist)
	if len(alist)>1:
		mid = len(alist)//2
		lefthalf = alist[:mid]
		righthalf = alist[mid:]

		mergeSort(lefthalf)
		mergeSort(righthalf)

		i=0
		j=0
		k=0
		while i < len(lefthalf) and j < len(righthalf):
			if lefthalf[i] < righthalf[j]:
				alist[k]=lefthalf[i]
				i=i+1
			else:
				alist[k]=righthalf[j]
				j=j+1
			k=k+1

		while i < len(lefthalf):
			alist[k]=lefthalf[i]
			i=i+1
			k=k+1

		while j < len(righthalf):
			alist[k]=righthalf[j]
			j=j+1
			k=k+1
	print("Merging ",alist)

alist = [54,26,93,17,77,31,44,55,20]
mergeSort(alist)
print(alist)
```
