def flatten(lst):
    global temp
    temp = []
    flatten_helper(lst)
    return temp

def flatten_helper(lst):
    for i in lst:
        if type(i) == list:
            flatten_helper(i)
        else:
            temp.append(i)

def reverse(lst):
    lst.reverse()
    for i in lst:
        if type(i) == list:
            reverse(i)
    return lst
