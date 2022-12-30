d = {}
d[0] = 1
d[1] = 1

inp = int(input())

if inp == 1:
    print(1)
else:
    for u in range(2,inp+1):
        c = 0
        for j in range(u, 0, -1):
            checkPrime = True
            target = j
            for i in range(2, int(target/2)+1):
                tt = target
                while(tt != 0):
                    temp = i
                    i = tt
                    tt = temp%tt
                gg = i
                if(gg!= 1):
                    checkPrime = False
            if(checkPrime):
                c+= d[u-j]
        d[u] = c

    print(d[inp])
