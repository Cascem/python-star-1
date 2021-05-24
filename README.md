# python-star-1
print star pattern python(1)
import sys
n = int(sys.stdin.readline())
for i in range(n):
    for j in range(i+1):
        print("*",end="")
    print("")
