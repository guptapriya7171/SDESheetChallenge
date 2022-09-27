# SDESheetChallenge  ![example workflow](https://img.shields.io/badge/DSA-Algo-blue)

<h3>The repository includes all important question along with an easy and the optimized solution.</h3>

Note:
Data structures are referred to as a collection of data values and relationships between them, functions, and operations applicable to the data. so that, users can easily access and modify the data efficiently. Data structures help us to manage large amounts of data, such as huge databases. Efficient data structures are the fundamental basis for efficient algorithms

# Searching
Searching in data structure refers to the process of finding the required information from a collection of items stored as elements in the computer memory. 

## Searching Methods
Searching in the data structure can be done by applying searching algorithms to check for or extract an element from any form of stored data structure.These algorithms are classified according to the type of search operation they perform, such as:

<h4> Sequential search </h4>
The list or array of elements is traversed sequentially while checking every component of the set.
<em><b>For example – Linear Search.</b></em>

<h4> Interval Search </h4>
The interval search includes algorithms that are explicitly designed for searching in sorted data structures. In terms of efficiency, these algorithms are far better than linear search algorithms.
<em><b>Example- Logarithmic Search, Binary search.</b></em>

# Sorting
Sorting is an arrangement of data in a particular order.
Some real-life examples of sorting are:-
<b>Contact List</b> in Your Mobile Phone also contains all contacts arranged alphabetically (lexicographically). So if you look for contact then you don’t have to look randomly and can be searched easily and many others like Apps on your phone.
<b>Keywords</b> in Your book are also in a lexicographical manner and you can find it according to Chapter.
The main advantage of sorting is time complexity and that’s the most important thing when you solve a problem because it’s not enough you’re able to solve a problem but you should be able to solve it in the minimum time possible. Sometimes problems can be solved easily and quickly based on sorting which can prevent you from every Coder’s Nightmare i.e. TLE (Time Limit Exceeded).
In depth study on sorting : https://www.codingninjas.com/codestudio/library/sorting-in-data-structure-categories--types

## Types of sorting
1. <b>Bubble Sort</b>: It’s one of the simplest algorithms which repeatedly iterates through the list, compares the elements next to each other, and swaps according to the condition passed to them.
2. <b>Insertion Sort</b>: Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.
3. <b>Selection Sort</b>: Selection sort works by repeatedly finding the smallest element from the array and then putting it in the beginning and then again finding the smallest from the rest of the array other than the previous one and arranging it in beginning. So basically we can say that it has two subarrays in it one is Sorted and the other is unsorted.
4. <b>Quick Sort </b>: It is based on partition. It is also known as partition exchange sorting. The basic concept of this algorithm is to pick one element from an array and rearranges the rest of elements around it and that element is known as pivot element and that element divides the main array into two sub-arrays. Once the pivot is fixed then it moves all the elements lesser than it to left and elements greater than it to right. This procedure is repeated recursively until there is one element left in the sub-array.
5. <b>Merge Sort</b>:Merge Sort is one of the most popular sorting algorithms that is based on the principle of Divide and Conquer Algorithm. Here, a problem is divided into multiple sub-problems. Each sub-problem is solved individually. Finally, sub-problems are combined to form the final solution.Although there is no. of sorting algorithms mostly used are discussed above and others are also important which is used in advanced Data Structure such as-

Heap Sort
Counting Sort
Bucket Sort
Radix Sort
Shell Sort
Comb Sort
Cycle Sort
Bitonic Sort
Tree Sort
Stooge Sort

<h4> Which sorting is best in data structures?</h4>
Every sorting algorithms have their own advantages and disadvantages. Select the sorting algorithm that is best fitted for your data. If you’re constrained in space the choose heap sort. If you need something stable choosing merge sort will help you. For almost sorted data, considering insertion sort is O(n) time! Inbuilt sorting algorithms use hybrid sorts which are combination of different basic sorting algorithms.

Quicksort is considered to be one of the fastest sorting algorithms. It is also considered to be the best sorting algorithm. Some of its features are that it is basically a comparison sort and can be done in-place in an array, however, inefficient implementation, it’s not a stable sort.
Though the worst-case complexity is O(n^2), on an average it gives us O(nlogn) time complexity. You can also think of considering Merge sort, which is very similar to Quicksort but has more complexity than quicksort.

![This is an image](https://www.codingninjas.com/blog/wp-content/uploads/2020/11/image-170.png)

Access Modifier:
The access modifiers in Java specifies the accessibility or scope of a field, method, constructor, or class.
The four access modifiers in Java are public, protected, default, and private.
In CN it was mentioned that there three modifier, might be an old video.
Include one more that is protected,
## Four Types of Access Modifiers
<h6>Private</h6>: We can access the private modifier only within the same class and not from outside the class.
<h6>Default</h6>: We can access the default modifier only within the same package and not from outside the package. And also, if we do not specify any access modifier it will automatically consider it as default.
<h6>Protected</h6>: We can access the protected modifier within the same package and also from outside the package with the help of the child class. If we do not make the child class, we cannot access it from outside the package. So inheritance is a must for accessing it from outside the package.
<h6>Public</h6>: We can access the public modifier from anywhere. We can access public modifiers from within the class as well as from outside the class and also within the package and outside the package.

