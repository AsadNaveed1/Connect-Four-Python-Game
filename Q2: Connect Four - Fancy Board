x= input("Standard game? (y/n): ")
if x=="y":
    F= input("Fancy board? (y/n): ")
else:
    r= int(input("r? (2 - 20): "))
    c= int(input("c? (2 - 20): "))
    F= input("Fancy board? (y/n): ")
if x=="y":
    if F=="n":
        r=5
        c=7
        for i in range(r,-1,-1):
            print(i,'· '*c)
        print("  ",end="")
        for j in range(c):
            print(j,end="")
            print(" ",end="")
        print()   
    else:
        r=5
        c=7
        for i in range(r,-1,-1):
            print(str(" ")+'+-'*c+'+')
            print(str(i)+'|'+'·|'*c)
        print(str(" ")+'+-'*c+'+')
        print("  ",end="")    
        for j in range(c):
            print(j,end="")
            print(" ",end="")
        print()           
else:
    if F=="n":
        r=r-1
        # init_space = len(str(c-1))-1 if len(str(c-1))-1 >= 0 else 0 
        init_space = 0
        if r>c-1:
            max_val=r
        else:
            max_val=c-1    
        side_right = (len(str(max_val))) if ((len(str(max_val))) -1) == 0 else (len(str(max_val))) -1
        side_left = (len(str(max_val))) -1
        # print(side_right, side_left)
        for i in range(r,-1,-1):
            if len(str(c-1))>1 and len(str(r))<=1:
                print(" "*side_left, end="") 
                init_space = side_left
            print(" "*(len(str(r))-len(str(i))), end="")
            print(str(i) + ' '*side_right + (' '*side_left +  '·' + ' '*side_right)*c)
        print(" "*(len(str(r))+ side_right + side_left + init_space), end="")
        min_space = side_right+side_left#(len(str(c)))
        for j in range(c):
            if(j!=c-1):
                print(j," "*(min_space-len(str(j+1))),end="")
            else:
                print(str(j) + " ")
    else: 
        r=r-1
        init_space = 0
        if r>c-1:
            max_val=r
        else:
            max_val=c-1     
        side_right = (len(str(max_val))) if ((len(str(max_val))) -1) == 0 else (len(str(max_val))) -1
        side_left = (len(str(max_val))) -1
        # print(side_right, side_left)
        for i in range(r,-1,-1):
            if r>9 or c>9:
                print(str("  ") + '+--'*c + '+')
            else:
                print(str(" ") + '+-'*c + '+') 
            if len(str(c-1))>1 and len(str(r))<=1:
                print(" "*side_left, end="") 
            init_space = side_left
            print(" "*(len(str(r))-len(str(i))), end="")
            print(str(i) + '|' + (' '*side_left +  '·|')*c)
        if r>9 or c>9:
            print(str("  ") + '+--'*c + '+')
        else:
            print(str(" ") + '+-'*c + '+') 
        if r>9 or(c>9 and r>9):
             print(" "*(len(str(r)) + side_left + init_space), end="")
        else:
            print(" "*(len(str(r)) + side_right + side_left + init_space), end="")
        min_space = side_right+side_left#(len(str(c)))
        for j in range(c):
            if(j!=c-1):
                print(j," "*(min_space-len(str(j+1))),end="")
            else:
                print(str(j) + " ")
