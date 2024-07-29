# Codsoft-Task-2
Design a simple calculator with basic arithmetic operations. Prompt the user to input two numbers and an operation choice. Perform the calculation and display the result
print("*********SIMPLE CALCULATOR********")


n1=int(input("enter number 1: "))

n2=int(input("enter number 2: "))


operator=input("enter operator: ")


text=''
match operator:
       case "+" :
              print("the sum of given numbers is ",n1+n2)

       case "-" :
              print("the difference of numbers is ",n1-n2)

       case "*" :
              print("the product of numbers is ",n1*n2)

       case "/" :
              print("the division of numbers is ",n1/n2)

       case "_":
              input("enter a valid operator")
       case default:
              print("the operator doesn't matchup")
            
