# PROBLEM-OF-THE-DAY

#FILL THE GRID


def tiles(count,n,m):
    if n%2==0 and m%2==0:
        return 0
    elif n%2==0:
        return n 
    elif m%2==0:
        return m
    else:
        return (n+m-1)
        
if __name__ == '__main__':
    t=int(input())
    for i in range(t):
        x,y=map(int,input().split())
        
        print (tiles(0,x,y))
