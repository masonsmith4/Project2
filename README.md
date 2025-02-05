# Project2
Bubble sort and pointers


set const max to 9

function printValues(array)
	for i from 0 to max - 1:
		print array[i]
	
	print the new line

constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)

function swap(a, b):
	temp  = a
	a = b
	b = temp

int main():
values as an array[] = {7, 3, 9, 4, 6, 1, 2, 8, 5}
printValues)values)

print before
print before swap

test swap below

x=3, y=5
print "x:", x, "y:", y'
swap(x, y)
print "x:", x, "y:", y

sort(values)
print after
printValues(values)

return 0

end yay
