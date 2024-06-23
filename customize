from random import randint

choices = ["FOLD", "UNFOLD"]

while True:
    p1 = int(input("Enter a Choice (0 for FOLD, 1 for UNFOLD):"))
    c2 = randint(0, 1)
    c3 = randint(0, 1)

    p1choice = choices[p1]
    c2choice = choices[c2]
    c3choice = choices[c3]

    if (p1choice == "FOLD" and c2choice == "FOLD" and c3choice == "UNFOLD") or \
       (p1choice == "UNFOLD" and c2choice == "UNFOLD" and c3choice == "FOLD"):
        print(p1choice, c2choice, c3choice, "c3 wins")
    elif (p1choice == "FOLD" and c2choice == "UNFOLD"):
        print("PLAYER - 1", p1choice, "c - 2", c2choice, "c3", c3choice, "P1 wins")
    else:
        print("PLAYER - 1", p1choice, "c - 2", c2choice, "c3", c3choice, "draw")
