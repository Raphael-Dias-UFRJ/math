from matplotlib import pyplot as plt
import numpy as np

number = int(input("initial number:"))
counting = 0
list = [number]

while number != 1:
    if (number % 2) ==0: #number is even
        number = number/2
    else: #number is odd
        number = (number*3)+1
    list.append(int(number))
    counting = counting + 1

print("TOTAL DE ETAPAS ATÉ A REPETIÇÃO:",counting)
print("SEQUÊNCIA:", list)

last_Natural_Number = int(input("Last Natural Number to create the list:"))
list_countings = []
for i in range(1,last_Natural_Number+1):
    counting_i = 0
    while i != 1:
        if (i % 2) ==0:
            i = i/2
        else:
            i = (i*3)+1
        counting_i = counting_i + 1
    list_countings.append(int(counting_i))

print("Number of repetitions of Collatz sequence on the Natural line up to",last_Natural_Number,":",list_countings)

x_data = range(1,last_Natural_Number+1)
y_data = list_countings

fig = plt.figure()
ax = fig.add_subplot(1, 1, 1)
ax.plot(x_data, y_data)
ax.set_xlabel('Natural Number')
ax.set_ylabel('Number of Collatz Repetitions')
