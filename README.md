# Data-structure-01
# ---------- ARRAY LIST ----------

class ArrayList:
    def __init__(self):
        self.arr = []

    def insert(self, value):
        self.arr.append(value)

    def remove(self, value):
        if value in self.arr:
            self.arr.remove(value)

    def display(self):
        print("Array List:", self.arr)


# ---------- LINKED LIST ----------

class Node:
    def __init__(self, data):
        self.data = data
        self.next = None


class LinkedList:
