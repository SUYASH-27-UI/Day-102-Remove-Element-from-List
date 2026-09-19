# Day-102-Remove-Element-from-List
# Python Day 102 - Remove Element from List

This program removes an element from a list using its index position.

## Example

Original List:

```text id="7v1x8c"
[10, 20, 30, 40, 50]
```

Input:

```text id="w4q2nt"
Enter index to remove: 2
```

Output:

```text id="2kq8sj"
Updated list: [10, 20, 40, 50]
```

## Concepts Used

* Lists
* Indexing
* `input()`
* `int()`
* `pop()` method
* Variables

## How It Works

1. Create a list of numbers.
2. Display the original list.
3. Ask the user for the index of the element to remove.
4. Use the `pop()` method to remove the element.
5. Display the updated list.

## Python Code

```python id="k2d5zs"
numbers = [10, 20, 30, 40, 50]

print("Original list:", numbers)

position = int(input("Enter index to remove: "))

numbers.pop(position)

print("Updated list:", numbers)
```

## Output

```text id="h8k3qv"
Original list: [10, 20, 30, 40, 50]
Enter index to remove: 2
Updated list: [10, 20, 40, 50]
```

## Goal

The goal of this project is to practice Python lists, indexing, user input, and the `pop()` method.
