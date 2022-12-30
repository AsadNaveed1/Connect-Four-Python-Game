r,c = 6,7  
F = 'n'      
x= input("Standard game? (y/n): ")

if x=="y":
    F= input("Fancy board? (y/n): ")
else:
    r= int(input("r? (2 - 20): "))
    c= int(input("c? (2 - 20): "))
    F= input("Fancy board? (y/n): ")

playableBoard = ""
if F=="n":
        resultBoard = ""
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
            if len(str(c-1))>1 and len(str(r))<=1:
                resultBoard+=" "*side_left 
                init_space = side_left
            resultBoard+=" "*(len(str(r))-len(str(i)))
            resultBoard+=str(i) + ' '*side_right + (' '*side_left +  '·' + ' '*side_right)*c + "\n"
        resultBoard+=" "*(len(str(r))+ side_right + side_left + init_space)
        min_space = side_right+side_left#(len(str(c)))
        for j in range(c):
            if(j!=c-1):
                resultBoard+=str(j) + " "*(min_space-len(str(j+1))+1)
            else:
                resultBoard+=str(j) + " "
else: 
        resultBoard = ""
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
                resultBoard+=str("  ") + '+--'*c + '+\n'
            else:
                resultBoard+=str(" ") + '+-'*c + '+\n'
            if len(str(c-1))>1 and len(str(r))<=1:
                resultBoard+=" "*side_left 
            init_space = side_left
            resultBoard+=" "*(len(str(r))-len(str(i)))
            resultBoard+=str(i) + '|' + (' '*side_left +  '·|')*c + "\n"
        if r>9 or c>9:
            resultBoard+=str("  ") + '+--'*c + '+\n'
        else:
            resultBoard+=str(" ") + '+-'*c + '+\n'
        if r>9 or(c>9 and r>9):
             resultBoard+=" "*(len(str(r)) + side_left + init_space)
        else:
            resultBoard+=" "*(len(str(r)) + side_right + side_left + init_space)
        min_space = side_right+side_left#(len(str(c)))
        for j in range(c):
            if(j!=c-1):
                resultBoard+=str(j)+" "*(min_space-len(str(j+1))+1)
            else:
                resultBoard+=str(j) + " "  
print(resultBoard)

# Game starts now
turn = 'X'
while(True):
    inp = input("player" + turn + " (col #): ")
    if(inp=='e'):
        print("bye")
        break
    cc = int(inp)
    board = resultBoard
    # resultBoard = fillBoard(int(inp), turn, resultBoard)

    rows = board.split('\n')
    # print(rows)
    endReached = False
    sp_delim = " " if F=='n' else "|"
    r=0
    for row in reversed(rows[:len(rows)-1]):
        if("+" in row):
            r+=1
            continue
        uu = 0
        columns = row.split(sp_delim)
        x = 0
        if("·" in row): # stil space left
            cols = columns
            i1,i2,i3=len(cols)+1,len(cols)+1,len(cols)+1
            cols2 = []
            for elem in cols:
                cols2.append(elem)
            for i in range(len(cols2)):
                ss = ""
                for ii in range(len(cols2[i])):
                    if(cols2[i][ii]==" "):
                        ss+= ""
                    else:
                        ss+=cols2[i][ii]
                cols2[i] = ss #repl(cols2[i], " ", "") #cols2[i].replace(" ","") 
            if("X" in cols2):
                i1 = cols2.index("X")
            if("O" in cols):
                i2 = cols2.index("O")
            if("·" in cols2):
                i3 = cols2.index("·")
            # print(min(i1,i2,i3))
            #return min(i1,i2,i3)
            x = min(i1,i2,i3) #findFirstIndex(columns)#columns.index('·')
            # print(x)
            # print(columns)
        else:
            r+=1
            continue
        for col in range(x, len(columns)):
            temp = columns[col]
            ss = ""
            for ii in range(len(temp)):
                if(temp[ii]==" "):
                    ss+= ""
                else:
                    ss+=temp[ii]
            temp = ss
            # print(temp, uu ,cc)
            #temp = repl(temp, " ", "") #temp.replace(" ", "")
            if (temp == "·" and uu==cc):
                # print("Reached")
                ss = ""
                for ii in range(len(columns[col])):
                    if(columns[col][ii]==temp):
                        ss+= turn
                    else:
                        ss+=columns[col][ii]
                columns[col] = ss
                #columns[col] = repl(columns[col], temp, turn) #columns[col].replace(temp, turn)
                rows[len(rows)-2-r] = sp_delim.join(columns)
                resultBoard = '\n'.join(rows)
                endReached = True
            if(endReached):
                break
            if(temp in ["·", "X", "O"]):
                uu+=1
        if(endReached):
            break
        rows[len(rows)-2-r] = sp_delim.join(columns)
        r+=1
    resultBoard = '\n'.join(rows)

    print(resultBoard)
    turn = 'O' if turn == 'X' else 'X'

