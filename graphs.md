from matplotlib import pyplot
x = []
y = []
for num in range(-10, 10):
    x.append(num)
    sum = num+1
    y.append(2**num-1)
    print("The y value for x: {}".format(num), "is : {} ".format(y))
    print(" ")

pyplot.plot(x, y)
pyplot.xlabel('the x axis')
pyplot.ylabel("the y axis")
pyplot.show()

![CarRental](Screen Shot 2020-02-23 at 14.48.47)
