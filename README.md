nums = [12, 45, 23, 67, 34]
print(max(nums))  #using max() function to find the maximum.
print(min(nums))  #using min() function to find the minimum.

marks = [45, 67, 89, 90]
print(sum(marks ))  #using sum() function to find the sum.

list1 = [1,2,3]
list2 = [4,5,6]
list3 = list1 + list2   #using arthimetic operator to combine the string.
print(list3)

names = ["John","Alice","Bob","Eve"]
a = names.index("Bob")  # using the index() we can find the index of an element.
print(a)

letters = ["a","b","c","d"]
print(letters[ : : -1])

numbers = [10,15,20,25,30]
print(numbers[ : : 2])  #prints only the even numbers because of step in slicing.

fruits = ["Apple","Banana","Cherry"]
fruits2 = fruits  # we assigned that list1 is equal to list2
print(fruits2)

nums = [1,2,3,2,4,2,5]
n = nums.count(2)
print(n)

marks = [45, 67, 89, 90]
a = marks.sort(reverse=True)  # the given list is already in sorted but to check we have used sort() again to check the list is in order or not.
print(marks)
