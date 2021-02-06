# GlobalAIHubPythonCourse
Homeworks

#HOMEWORK 1 :
# CREATE List and swap the second half of the list with the first half of the list and print the list on the screen:
list=[10,25,56,48]
list1=[]
list2=[]
swap_list=[]
for i in list:
    if list.index(i)<len(list)/2:
        list1.append(i)
    elif list.index(i)>=len(list)/2 and list.index(i)<=len(list):
        list2.append(i)
for i in list2:
    swap_list.append(i)
for i in list1:
    swap_list.append(i)
print(swap_list)

#homework 2
#ask user input n and print out all even number from 0 to n:

n=input('enter an digit integer n:') #ask user n 
n_int=int(n) #change type str to int
for i in range(0,n_int+1): # range which includes the n 
    if i%2==0: # even numbers
        print(i)
