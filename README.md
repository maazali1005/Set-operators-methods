# Set-operators-methods
#adding an element
s1={1,2,3,4}
s1.add(5)
print(s1)
O/P:{1, 2, 3, 4, 5}

#updating elements into another set
s2={'a','b','c','d'}
print('consider another set:',s2)
s1.update(s2)
print(s1)
consider another set: {'b', 'd', 'a', 'c'}
o/p:{1, 2, 3, 4, 5, 'd', 'a', 'c', 'b'}

#removing an element
d=input('enter the element to remove')
s1.discart(d)
print(s1)
O/P:enter the element to remove:c

#union operation
s1={1,2,3,4,5}
s2={6,7,8}
s3=s1.union(s2)
print(s3)
O/P:{1,2,3,4,5,6,7,8}

#intersection
s1={1,2,3,4,5}
s2={1,2,3,4,5,6,7,8}
s3=s1.intersection(s2)
print(s3)
O/P:{1, 2, 3, 4, 5}
