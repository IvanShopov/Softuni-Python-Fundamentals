def isPerfect(number, sum):
    if number>1:
        for divisor in range(1, number):
            if number % divisor == 0:
                sum += divisor
    if sum == number or number==1:
        return "We have a perfect number!"
    else:
        return "It's not so perfect."


number = int(input())
sum = 0
print(isPerfect(number, sum))
