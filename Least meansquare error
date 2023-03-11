w1=w2=w3=w4=b=float(input("Enter intial value: "))
al=float(input("Enter learning rate: "))
n=int(input("Enter no of epochs: "))
mse=0
z=0
for i in range(4*n):
    x1=int(input("x1"))
    x2=int(input("x2"))
    x3=int(input("x3"))
    x4=int(input("x4"))
    t=int(input("t"))
    yin=x1*w1+x2*w2+x3*w3+x4*w4+b
    w1=w1+(al*x1*(t-yin))
    w2=w2+(al*x2*(t-yin))
    w3=w3+(al*x3*(t-yin))
    w4=w4+(al*x4*(t-yin))
    b=b+(al*(t-yin))
    mse=mse+(t-yin)*(t-yin)
    print(yin,t-yin,w1,w2,w3,w4,b,(t-yin)*(t-yin),sep=' ')
    z+=1
    if(z==4):
        print("MSE=",mse)
        z=0

