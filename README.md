# basic_py-patikadev
#project_1

l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
types = [list, tuple, dict]
def out(l):
    for i in l:
        if type(i) in types:
            for m in i:
                l.append(m)
            l.remove(i)

    
for i in range(len(l)):
    out(l)



#project_2

l = [[1, 2], [3, 4], [5, 6, 7]]
new_list = []


def reverse_it(l):
    for m in l:
        m.reverse()
        new_list.append(m)
    return new_list.reverse() 

reverse_it(l)
