

# Sorting Algorithms Visualizer

Sorting Algorithms Visualizer (SAV) produes visuals instead of long codes to understand the algorithms.Sorting can be referred to as arranging files in some particular order. The arrangement performed can be based on the value of each file present. That particular order can be in either an ascending or descending fashion. Sorting algorithms are instructions given to a computer to arrange elements in a particular order.

## Prerequisites
- Node.js
- Basic Knowledge of JavaScript

## Categories of sorting algorithms

- Internal sorting algorithms: These are sorting algorithms applied to a small amount of data. Only the main memory is used. Examples would be bubble sort, insertion sort, and quicksort.

- External sorting algorithms: These are sorting algorithms that can be applied to massive amounts of data. As a result, external storage devices such as hard drives, and flash disks are used. An example would be merge sort.

## Efficiency of sorting algorithms
Some sorting algorithms are more efficient than others. The effectiveness of a sorting algorithm is usually defined by the following performance measures:

- Time complexity: This is the amount of time required by the computer to perform the sorting based on an algorithm.

- Memory complexity: It is the amount of computer memory required by the computer to perform the sorting based on an algorithm.

#### Based on the factors above, an algorithm has four performance cases:

- Worst case time complexity: It is a function defined as a result of a maximum number of steps taken on any instance of size n. It is usually expressed in Big O notation.

- Average case time complexity: It is a function defined as a result of the average number of steps taken on any instance of size n. It is usually expressed in Big theta notation.

- Best case time complexity: It is a function defined as a result of the minimum number of steps taken on any instance of size n. It is usually expressed in Big omega notation.

Space complexity: It is a function defined as a result of additional memory space needed to carry out the algorithm. It is usually expressed in Big O notation.

## Strategies applied during sorting
- Recursion: Recursion is a programming method where you define a function in terms of itself. The function generally calls itself with slightly modified parameters (in order to converge).

- Divide and conquer: The algorithm accomplishes its task by dividing the problem into smaller subproblems and solving them to come up with the overall solution.

## Types of Sorting Supported
### Merge Sort
Merge sort uses the divide and conquer technique. The main concept of merge sort is that an array of length 1 is sorted. The task, therefore, lies in splitting the array into subarrays of size 1 and then merge them appropriately so that it comes up with the sorted array.

##### Step-by-step guide
- Split the array elements into individual elements.

- Compare the individual elements and arrange them in order. This results in subarrays of length 1 or 2.

- Make an empty array.

- Compare the elements of the subarrays and push the smaller of the values to the empty array.

- If you had extracted all the values from one of the arrays, push the remaining array to the new array.

- Continue until all subarrays have been covered and you have one sorted array.

![image](https://user-images.githubusercontent.com/68835688/129846083-3e734763-1cbc-4380-b6a2-74ad6bf522a5.png)

### Bubble Sorting

Bubble sort follows the recursion technique.

##### Step-by-step guide:
- Start by comparing the first two elements in an array.

- Swap them if required.

- Continue till the end of the array. At this point, you have made a series of inner passes and completed an outer pass.

- Repeat the process until the entire array is sorted.

![image](https://user-images.githubusercontent.com/68835688/129846209-81996fb1-211a-4093-938d-9226c85c6cd8.png)


### Insertion Sort
Insertion sort uses the recursion technique. There is a portion of the array that is sorted and the other that is unsorted. So you have to compare the elements from the unsorted portion one by one and insert them into the sorted portion in the correct order. In the guide below we are using ascending order.

##### Step-by-step guide
- Start by comparing the second element of the array with the first element assuming the first element is the sorted portion. Swap if the second element is smaller than the first element.

- Iterate through comparing the first element with each element of the unsorted portion. If the element from the unsorted portion is smaller than the first element, swap.

- After iterating through the entire array, increment the sorted portion to the next index and recursively compare the value of the last index of the sorted portion with each value of the unsorted portion. Swap where the value of the unsorted portion is smaller.

- The sorted portion shall increase until it covers the entire array yielding a sorted array.

![image](https://user-images.githubusercontent.com/68835688/129846428-5c42a81b-a6f9-48f5-9142-a828c9c3aab2.png)

### Selection Sort
Selection sort uses the recursion technique. In the guide below, we are using ascending order. For descending order, you do the reverse.

##### Step-by-step guide
- Given an array, assume that the first element in the array is the smallest.

- From the other portion of the array, find the minimum value, and swap it with the first element. At this point, you have completed the first pass.

- Repeat the same procedure with the rest of the array comparing the elements to the right, not the left.

![image](https://user-images.githubusercontent.com/68835688/129846652-a111d174-7555-4b95-b175-d07f0b379c30.png)

### Quick Sort
Quicksort applies the divide and conquer technique as well. It works by having a pivot element such that the elements to the left of it are less than it and those to the right are greater than it. The pivot element can be any element in the array.

##### Step-by-step guide
- Select a pivot element.

- Split the array into two arrays with those less than the pivot element on the left and those greater than the pivot element to the right.

- Carry out the above steps recursively until we have subarrays of length 1. Combine the subarrays to yield a sorted array

![image](https://user-images.githubusercontent.com/68835688/129846726-2d8e3a52-954b-42a4-83e9-f893edcbc4f0.png)


## Live at 

https://visualizer.tk/


## Acknowledgements

 - [Resource 1](https://www.youtube.com/watch?v=pFXYym4Wbkc)
 - [Resource 2](https://www.section.io/engineering-education/sorting-algorithms-in-js/)
 - [Resource 3](https://medium.com/@rajat_m/implement-5-sorting-algorithms-using-javascript-63c5a917e811)

  
## Authors

- [Aryaman Srivastava](https://www.github.com/AryamanSrii)

  
## License

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

  ## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Graph | ![rgb(45,41,38)](https://via.placeholder.com/10/e94b3cff?text=+)
| Background | ![#f8f8f8](https://via.placeholder.com/10/2d2926ff?text=+)  |
| Buttons | ![#00b48a](https://via.placeholder.com/10/e94b3cff?text=+)  |
| New Array Buttons | ![#00d1a0](https://via.placeholder.com/10/c0c0c0?text=+) |


## Demo



https://user-images.githubusercontent.com/68835688/129765317-a161d7a7-a205-4f5f-8e4c-9eb4677a2559.mp4


  
## FAQ

#### How Many Sorting Algorithms does the app support?

5

#### Which Language is it coded in?

HTML CSS AND JS

  
## 🚀 About Me
Aryaman Srivastava is an inquisitive, young lad, with a deep passion for keeping up with the latest trends in tech. Being only 14 years, he doesn't let his age stop him or quit; instead, he uses it to his advantage, making use of the extra time he has to explore as well as study programming along with other hot topics in the field of computer science. He is particularly passionate about AI, and follows the latest developments in the field.
  
## Screenshots
#### Full Page
![Full Page](https://media.discordapp.net/attachments/829696850700402740/877203092754559006/screenshot.png?width=748&height=623)

#### Header
![Header](https://media.discordapp.net/attachments/829696850700402740/877203058608705646/unknown.png?width=540&height=98)

#### Algorithms
![Algorithms](https://media.discordapp.net/attachments/829696850700402740/877203131652530256/unknown.png?width=1440&height=82)

#### Graph
![Graph](https://media.discordapp.net/attachments/829696850700402740/877203187596161064/unknown.png?width=730&height=551)

#### Size and Speed
![Size and Speed](https://media.discordapp.net/attachments/829696850700402740/877203258739929128/unknown.png?width=1261&height=68)
