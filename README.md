# python_code
def main():
    x=0
    y=0
    d=[[0 for i in range(3)] for j in range(3)]
    


    while(x<3):
        while(y<3):
            try:
                d[x][y]=int(input("Number[%d][%d]: " %(x,y)))
                y+=1
            except:
                ("Enter Integer Value!")
        y=0
        x+=1

    print()
    print("Result:")
    print()
    print("| %d  %d  %d |" %(d[0][0], d[0][1], d[0][2]))
    print("| %d  %d  %d |" %(d[1][0], d[1][1], d[1][2]))
    print("| %d  %d  %d |" %(d[2][0], d[2][1], d[2][2]))



if __name__ == "__main__":main()
