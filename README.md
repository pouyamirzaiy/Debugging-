# Exercise 1

The bug happened because a set was used for indexing. Sets do not keep the order of items, so the wrong fruit was returned. I fixed it by using a list instead of a set.

---

# Exercise 2

The coordinates were swapped incorrectly, and some values were overwritten during the process. I fixed this by safely swapping the x and y values using a copied array.

---

# Exercise 3

The graph was wrong because the x-axis and y-axis were mixed up. Also, the CSV values were read as strings instead of numbers. I fixed both issues so the plot matches the data correctly.

---

# Exercise 4

The main bug happened because the code used a fixed batch size instead of the real batch size from the DataLoader, which caused shape mismatch errors. I fixed it by using the current batch size during training.

The second bug was only visual and affected when generated images were displayed during training. I fixed the condition so images are shown at the correct time.
