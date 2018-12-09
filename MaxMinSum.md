


Python: min(big_array), max(big_array)

If you are allowed to use built-in functions of Python, then finding the min, max, and sum of the elements in the array is easy:

number = raw_input('Enter number:')
list_of_numbers = number.split()

numbersInt = map(int, list_of_numbers) # convert string list to integer list

- print "Size:",    len(numbersInt)
- print "Min:",     min(numbersInt)
- print "Max:",     max(numbersInt)
- print "Sum:",     sum(numbersInt)
- print "Average:", float(sum(numbersInt))/len(numbersInt) if len(numbersInt) > 0 else float('nan')
where numbersInt = map(int, list_of_numbers) converts each string number of the list to an integer. 

Each function has the following meaning:
- len computes the length of a list
- min computes the minimum
- max computes the maximum
- sum computes the sum of a list
- There isn't a mean function in Python standard library. But you can use numpy.mean() instead.
