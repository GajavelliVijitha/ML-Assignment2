# ML-Assignment2
ML Assignment_2
1.
for i in range (1,10):
    if(i<6):
        for j in range(0,i):
            print("*",end=" ")
        print("")
    else:
        x=i-5
        for j in range(0,5-x):
            print("*",end=" ")
        print("")
        
2.
print("\n\n\n")
my_list = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]
for i in range(0,len(my_list)):
    if(i%2==1):
        print(my_list[i])
        
3.        
print("\n\n\n")
x = [23, 'Python', 23.98]
xt=[]
for i in x:
    xt.append(type(i))
print(x)
print(xt)

4.
print("\n\n\n")
Sample_List=[1,2,3,3,3,3,4,5]
Unique_List=list(set(Sample_List))
print(Unique_List)

5.
print("\n\n\n")
Input_String='The quick Brow Fox' #input()
uppercasealpha=0
lowercasealpha=0
for i in Input_String:
    if(i.isupper()):
        uppercasealpha+=1
    else:
        if(i.islower()):
            lowercasealpha+=1
print("No. of Upper-case characters: "+str(uppercasealpha))
print("No. of Lowwer-case characters: "+str(lowercasealpha))
print("\n")
