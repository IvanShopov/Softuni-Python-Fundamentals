cardDeck = input().split(' ')
shuffles = int(input())
fixed_list = cardDeck[1:len(cardDeck) - 1]
halfDeck = int(len(fixed_list) / 2)
temp_list = []
for i in range(shuffles):
    for i, b in zip(fixed_list[:halfDeck], fixed_list[halfDeck:]):
        temp_list += [b, i]
    fixed_list = temp_list
    temp_list = []
cardDeck[1:len(cardDeck) - 1] = fixed_list
print(cardDeck)
