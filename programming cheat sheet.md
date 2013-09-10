# Programming cheat sheet
## Variable
A variable is a piece of memory which can hold a value, for example the number 42 or a string like "foo".
## Lists
A list enables you to store multiple items in a single variable. 
An empty list is built like this: `a = []`
### Create a list with items
`my_list = [1, 2, 3, 4, 5]`

### Add an item to a list
`my_list.push(6)`

## Loop
A loop is a construct which enables you to do specific things several times consecutively.
For example you want to print five times "Hello there!", you would write:
```Ruby
	for i in 1..5
		puts "Hello there!"
	end
```
### Loop through a list
You want to output every element of a list:
```Ruby
my_list = [1, 2, 3, 4, 5]
my_list.each do |element|
	puts element
end
```
`each` is a method called on the list which says we want the following code to be executed for every element in our list.
The variable `element` points to the current element of the list.
Everything between `|element|` and `end` will be executed for *every* item in the list, here in this case `puts element`.
## Function
You can think of a function like a mathematical function:
`f(x) = x * 2`.
A function has a name, in this case `f`, a parameter `x`, and a body `x * 2`. 
