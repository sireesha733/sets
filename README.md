# sets
#sets
#operations are union,intersection,symmetric diference,difference
set_1={1,2,3,4,5}
set_2={3,4,5,6,7}


#union
print(set_1 | set_2)
print(set_1.union(set_2))

#intersection
print(set_1 & set_2)
print(set_1.intersection(set_2))

#symmetric difference
print(set_1^set_2)

#difference
print(set_1.difference(set_2))

#subset,super set and disjoint
m={1,2,4}
n={1,2,3,4,5}

#issubset()
print(m.issubset(n))
print(n.issuperset(m))
print(m.isdisjoint(n))
