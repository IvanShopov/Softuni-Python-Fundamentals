command = input()
notes = [[] * 0 for i in range(10)]
while command != "End":
    tokens = command.split("-")
    index = int(tokens[0]) - 1
    element = tokens[1]
    notes[index].append(element)
    command = input()
result = []
for note in notes:
    if len(note) > 0:
        for n in note:
            result.append(n)
print(result)
