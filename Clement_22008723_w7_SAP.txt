import math
import random

while True:
    
    try:
        studentID = eval(input("Please enter your student ID "))
        name = input("Please enter your name ")
        semNums = eval(input("Please enter the numbers of semesters you did "))
        examScore = eval(input("please enter your score "))
        break
    except:
        print("please check your answer")





print("SUMMARY OF PROGRAM", "\n=======================")
print("Student ID: ", studentID)
print("name: ", name)
print("Exam Score: ", examScore)



if examScore >= 90 <= 100:
    grade = "A"

elif examScore >= 80 <= 89:
    grade = "B"
    
elif examScore >= 70 <= 79:
    grade = "c"
    
elif examScore >= 60 <= 69:
    grade = "D"
    

elif examScore >= 0 <= 59:
    grade = "F"

print("Grade: ", grade)



if semNums == 3 and grade == "A":
    group = "Soaring the Eagles"

elif semNums == 3 and grade == "b":
    group = "Soaring the Eagles"

elif semNums == 2 and grade == "C":
    group = "Guiding the Cubs"

elif semNums == 2 and grade == "D":
    group = "Guiding the Cubs"

elif semNums == 1 and grade == "F":
    group = "Coaching the Pandas"

else:
    group = "Currently unavailable"

print("Self-improvement program: ", group)




    




