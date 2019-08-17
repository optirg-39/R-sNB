# R-sNB

a = 1
b = 2
sum = 2
for i in range(50):
    c = a+b
    if c<4000000:
        a = b
        b = c
        if c%2==0:
            sum+=c
print(sum)
