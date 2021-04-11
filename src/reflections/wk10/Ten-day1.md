What are the three categories of data types? How are they different?

Value Type - this is a data type that holds a value in a memory space.
Reference Type - References the memory location of a value
Pointer Type - defines the data and the placeholder at the same time. Using the * identifier allow you to name several identifiers on a similar type.

What are the Value-type data types? What differences do you notice from JavaScript?
Value types in C# are bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort. 
 Each of these represent at value type that is held in a memory space under a variable declared after the types. 
 In Javascrip it is unecessary to declare types because javascript doesn't pay attention as strictly to memory allocation as C#. The value types listed here each are only allowed to take up a certain amount of memory in their respective memory space. Sometimes it is necessary to change value types for one variable as it's memory needs become greater or less than needed. You'll need to explicitly change the variable type if the precision of the value needs to increase, however, a value type can change implicityly if the memory needs of the value, and therefore the memory allocation are less than what was originally needed. 

In your own words how do Reference types get stored in memory? How does this differ from Value types? A reference type points to a memory space, and has little to do with what is contained in that space. It says that we want to know the address of this piece of information and that address is named this name. Value types assign a variable to a specific piece of information that is held in a memory space.