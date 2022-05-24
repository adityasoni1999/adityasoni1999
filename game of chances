from random import randint
number_range=input("enter number range seperated by space: ").split()
if 1<=len(number_range)<=2:
    start=int(number_range[0])
    end=int(number_range[1])
    random_number=randint(start,end)
    chances=5
    while chances>0:
        user_input=int(input("guess the number: "))
        if user_input>end or user_input<start:
            print("wrong answer. try again")
            continue
        else:
            if user_input>random_number:
                print("nummber is smaller...better luck next time")
            elif user_input<random_number:
                print("number is greater...better luck next time")
            else:
                print("gotcha...congratulations")
                break
            chances=chances-1
            if chances==0:
                print("out of chances..better luck next time")
else:
    print("wrong input!")
