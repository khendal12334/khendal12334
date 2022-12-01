print("===========WELCOME TO QUIZ GAME============")
print("-------------------------------------------")
player=input("PLAYER NAME IS:")
print("WELCOME USER",player)
print("-------------------------------------------")
score=0

while True:
    print("================YOU ARE NOW ON THE EASY MODE.================")
    print("================THE QUIZ GAME WILL NOW BEGIN.================")
    q1=input("""
    1.What does the equality operator do?
    A.It checks if a string is equal to other string.
    B.It checks if a string is greater than another
    >>> """).upper()

    if q1=="A":
        print("YOU GOT THE CORRECT ANSWER!")
        score=score+1
        print("YOU HAVE NOW A SCORE OF",score)
    else:
        print("WRONG ANSWER!")
    q2=input("""
        2.Which of these is the equality operator
        A. =
        B. == 
        >>> """).upper()

    if q2=="B":
            print("YOU GOT THE CORRECT ANSWER!")
            score=score+1
            print("YOU HAVE NOW A SCORE OF",score)
    else:
            print("WRONG ANSWER!")

    q3=input("""
            3.Identify the modulo operator.
            A.%
            B.#
            >>> """).upper()
    if q3=="A":
            print("YOU GOT THE CORRECT ANSWER!")
            score=score+1
            print("YOU HAVE NOW A SCORE OF",score)
    else:
            print("WRONG ANSWER!")
            print("TOTAL POINTS GAIN IS:",score)

            if score<2:
                    print("REMARKS: FAILED")
                    print("YOU CANNOT MOVE TO NEXT LEVEL")
                    p = (score / 3) * 100
                    print(format(p, '.1f'))
                    playAg = input("""Do you want to play again Y/N?
                    >>>""").upper()
                    if playAg == "Y":
                        pass
                    else:
                        print("Thankyou for playing our game!")
                    break

            else:
                p = (score / 3) * 100
                print(format(p, '.2f'))
                print("REMARKS: PASSED")
                print("NEXT LEVEL")

    print("""
    YOU ARE NOW ON THE MEDIUM MODE.THE QUIZ WILL NOW BEGIN""")
    point = 0
    q1 = input("""
    1.What are usually used in creating a more than a line
    A.THREE QUOTATION
    B.TWO QUOTATION
    >>> """).upper()
    if q1 == "A":
        print("YOU GOT THE CORRECT ANSWER")
        point = point + 1
        print("YOU HAVE NOW A SCORE OF", point)
    else:
        print("WRONG ANSWER!")

    q2 = input("""
    2.What is the purpose of variable in coding?
    A. It helps perform calculations and store data.
    B. Used to store information to be referenced and manipulated in a computer program
    >>> """).upper()
    if q2 == "B":
        print("YOU GOT THE CORRECT ANSWER!")
        print("YOU HAVE NOW A SCORE OF", point)
    else:
        print("WRONG ANSWER!")

    q3 = input("""
    3.What is the purpose of else statement?
    A. An alternative statement that is executed if the result of a previous test condition evaluates to false
    B. Let your program know whether or not is should execute a block of code
    >>> """).upper()
    if q3 == "A":
        print("YOU GOT THE CORRECT ANSWER!")
        point = point + 1
        print("YOU HAVE NOW A SCORE OF:", point)
    else:
        print("WRONG ANSWER!")


        print("THE TOTAL POINTS GAIN IS:", point)
        if point <=2:
         print("REMARKS: FAILED")
         print("YOU CANNOT MOVE TO NEXT LEVEL")
         p = (score / 3) * 100
         print(format(p, '.1f'))
         playAg = input("""Do you want to play again Y/N?
         >>>""").upper()
         if playAg == "Y":
             pass
         else:
             print("Thankyou for playing our game!")
         break
    if score >=2 or score <=3:
     p = (score / 3) * 100
     print(format(p, '.2f'))
     print("REMARKS: PASSED")
     print("NEXT LEVEL")


    print("""
    YOU ARE NOW ON HARD MODE.THE QUIZ GAME WILL NOW BEGIN""")
    correct = 0
    q1 = input("""
    1. What is the correct way to increment a value of 1 in phyton?
    A. num == num % 1
    B. num+=1
    >>> """).upper()
    if q1 == "B":
             print("YOU GOT THE CORRECT ANSWER!")
             correct = correct + 1
             print("YOU HAVE NOW A SCORE OF:", correct)
    else:
             print("WRONG ANSWER!")
    q2 = input("""
        2.How do you create a variable with the numeric number of 5
        A. X=5
        B. X=Input(5)
        >>> """).upper()
    if q2 == "A":
             print("YOU GOT THE CORRECT ANSWER!")
             correct = correct + 1
             print("YOU HAVE NOW A SCORE OF:", correct)
    else:
             print("WRONG ANSWER!")
    q3 = input("""
            3.What is the extension of phyton file?
            A. Pyt
            B. Py 
            >>> """).upper()
    if q3 == "B":
                print("YOU GOT THE CORRECT ANSWER")
                correct = correct + 1
                print("YOU HAVE NOW A SCORE")
