# task-4a
#create a tuple:define a tuple with elements of different data types(10,'hello',3.14,'world')
tuple=(10,'hello',3.14,'world')
print(tuple)
#access elements:access individual elements and slices of the tuple.
for i in tuple:
  print(i)
print(tuple[1:3])
print(tuple[:-1])
#concatenate tuples:combine two tuples to create a new tuple.
t2=(0,0.5)
t3=tuple+t2
print(t3)
#Immutable Nature:attempt to modify elements of the
tuple and handle the resulting error.
tuple(3)="PI"#ERROR
