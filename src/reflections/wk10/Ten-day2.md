What is a List in C#? 

A list can be a value type or a reference type. It creates an object that can contain a group of strings, or integers or it can be a reference to a group of abstracted items or other lists. 

What List methods seem like you might use them often? Why? 

The most common methods would be methods that use the same CRUD methods found in javascript controllers. The constuctor(Create), which creates a list, the list[index] and binarySearch methods, which would help you find a specific index and or a value in the list(Read), List.Add and list.clear, would update the list as in an edit, and removes in delete.

How would you retrieve an item from a list? What method could you use? 

List.find would return the first instance of the item desired in the predicated. This uses the index or position of the item in the list. In a list of three integers, list.find(2) would return the last item in the list. 