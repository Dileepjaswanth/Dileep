n=int(input())
def getProduct(n): 
    product = 1
    while (n != 0): 
        product = product * (n % 10) 
        n = n // 10
    return product 
print(getProduct(n))
