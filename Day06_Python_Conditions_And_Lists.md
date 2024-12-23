
# Day 6: Conditionals and Lists


Goal: To get an overview about 
- the different type of conditionals that we can use in Python 
- lists: creating different lists, reading them and doing operations on it


## Schedule


| Start  | End   | Activity                     |
| :--------- | :-------- | :--------------------------- |
| 09:00      | 09:30     | Protocol Review              |
| 09:30      | 10:00     | Guide Lecture                |
| 10:00      | 11:20     | Lecture: Conditions          |
| 11:25      | 12:00     | Exercise: Conditions         |
| 12:00      | 12:30     | Exercise Review              |
| 12:30      | 13:00     | Lists                        |
| 13:00      | 14:00     | Lunch                        |
| 14:00      | 14:45     | Lists (Continuation)         |
| 14:50      | 16:00     | Lens, Extend, Slicing        |
| 16:00      | 16:40     | Exercise                     |
| 16:40      | 17:40     | Review Exercise              |




## C1. onditions


You can make decisions based on whether an expression evaluates to True or False. This expression can be a numeric comparison, variable comparison, or other conditions, such as checking if a list is empty or if a number is within a certain range.


HOW?
Important when we are creating lists is:
-  not to forget to use [ ]
and
- that we can combine different type of variables (int, string, etc.)


### 1.1 If, else if,

| Method             | Goal                                                                |
| ----------------- | ------------------------------------------------------------------ |
| if | Checks if a condition is true or false.
| elif | Means ELSE IF. It is used to check at least more than one condition | 
| else | If the previous conditions not meet, then... do this| 


### 1.2 Logical Operators
| Operator             | explanation                                                                |
| ----------------- | ------------------------------------------------------------------ |
| And | All the conditions need to be true
| Or | At least one of the conditions should be true
| Not | It inverts the result of an operation (If it is true, not will then make it false)

 
## 2. Lists


WHY are lists so important? 
Because variable have some limitations

HOW?
Important when we are creating lists is:
-  not to forget to use [ ]
and
- that we can combine different type of variables (int, string, etc.)

For example


```bash
namecounts = ['Rossman', 12051, 'Neukölln', 12.10, 'Buenos Aires']
```

We can also make lists of lists, that is, to combine them
```bash
namecounts = ['Rossman', 12051, 'Neukölln', 12.10, 'Buenos Aires']
```
For example here we have a list containing 3 lists 

```bash
my_list_of_lists = [[42, 88, 99], ['Berlin', 'Paris', 'Tokyo'], [3.14, 'value', True]]
```

### 2.1 How to read the info?
There are two ways:
- Index (starts from 0)
and
-  a negative index (that is, starts from the end and not with 0, but with -1)

### 2.2 List methods
Some of the methods we saw:


| Method             | Goal                                                                |
| ----------------- | ------------------------------------------------------------------ |
| new_list.append() | Adds a **single**  element to the end of the list
| new_list.extend() | Adds **multiple** | 
| new_list.sort() | Sorts the elements of the list in ascending order.| 
| new_list.index() | Returns the index of the first matching element.
| new_list.remove() | Sorts the elements of the list in ascending order.| 
| new_list.pop() | removes an element by index (or the last element by default)| 
| new_list.slicing() | to extract a subset of the list based on range indexes| 


 
 ❗  For the **sorting** there are two way of showing the information : ascending or descending order.
 By default is ascending.
 If we want to set it as descending, then we need to use the parameter
 
 Reverse = true

my_list = [3, 1, 4, 2]
my_list.sort(reverse=True)
print(my_list)  

❗❗ Not to confuse

- Pop and Remove: pop() removes an element by index (or the last element by default), while remove() removes an element by value (not by index).
- Append and Extend: append() adds a single element to the list, while extend() adds multiple elements 


## Links

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
