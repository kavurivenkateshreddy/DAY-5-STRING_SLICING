"""
Date: 25th April 2022 Monday
Name: kavuti venkatesh reddy
File Desc: String Slicing
"""

x='apartment'
print(x)      #apartment
print(x[0]) # a
print(x[1]) # p
print(x[2]) # a
print(x[3]) # r
print(x[8]) # t
# print(x[9]) # IndexError: string index out of range

x='apartment'
print(x[1]+x[2]+x[3]+x[4]) # part
print(x[7]+x[6]+x[8]) # net
#print(x[3]+x[9]) #IndexError: string index out of range

x='venkatesh'
print(x[:])  #venkatesh
print(x[0:]) #venkatesh
print(x[1:]) #enkatesh
print(x[2:]) #nkatesh
print(x[3:]) #katesh
print(x[4:]) #atesh
print(x[5:]) #tesh
print(x[6:]) #esh
print(x[7:]) #sh
print(x[8:]) #h
print(x[9:])   #blank line
print(x[0:4]) #venk
print(x[2:5]) #nka
print(x[2:3]) #n
print(x[5:1]) # blank line 
print(x[4:3]) # blank line
print(x[:6])  #venkat

x='venkatesh'
print(x[-1])    #h
print(x[-2])    #s
print(x[-7])    #n
print(x[:-1])   #venkates
print(x[:-4])   #venka
print(x[:-6])   #ven
print(x[2:-4])  #nka 
print(x[-5:-3]) #at