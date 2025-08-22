✨ Features

* Initialization: Kick things off by crafting a brand new, empty list.
* Appending: Effortlessly stack several elements onto the end of your list.
* Inserting: Adding an element at a specific position.
* Extending: Merging one list with another.
* Popping: Removing the last element from a list.
* Sorting: Arranging list elements in ascending order.
* Indexing: Finding the position of a specific element.

🚀 Getting Started

To run this script on your local machine, follow these simple steps.

Prerequisites

Make sure you have Python 3 installed. You can check your version by running:

python --version


Instructions

1. Clone the repository:

git clone https://github.com/your-username/your-repository-name.git


1. Navigate to the directory:

cd your-repository-name


1. Run the script:

python list_operations.py


You will see the output in your terminal, showing the state of the list after each operation.

💻 Code Explanation

The script performs the following operations in sequence:

1. Create an empty list called my_list.

my_list = []



1. Append elements 10, 20, 30, 40 to my_list.

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)



1. Insert the value 15 at the second position (index 1).

my_list.insert(1, 15)



1. Extend my_list with another list: [50, 60, 70].

my_list.extend([50, 60, 70])


1. Remove the last element from my_list.

my_list.pop()



1. Sort my_list in ascending order.

my_list.sort()


1. Find and print the index of the value 30.

index_of_30 = my_list.index(30)
print(f"The index of the value 30 is: {index_of_30}")



