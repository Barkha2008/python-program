# python-program
def getPairsCount(arr,n,sum):
    count=0
    for i in range(0,n):
        for j in range(i+1,n):
            if (arr[i] + arr[j]== sum):
                count+=1
    return count

arr = [2,6,-2,2,3,1,2,2]
n=len(arr)
sum=6
c=getPairsCount(arr,n,sum)
print("Pairs count is :",c)
