# python-week-1-assignment
assignment
Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division).
Perform the operation based on the user's input and print the result.
Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.

print("Perform Arithmetic Functions With ease")
value_1=float(input('Enter N.o '))
value_2=float(input('Enter N.o '))
operation_sign=input("Enter Sign ") 
def Solution():
    def Addition():
        sum=value_1 + value_2
        print("Sum is " + str(sum))
    

    def Substraction():
        sum=value_1 - value_2
        print("Difference is " + str(sum))    
    
    
    def Division():
        sum=value_1 / value_2
        print("Quotient is " + str(sum))  
 
    
    def Multiplication():
        sum=value_1 * value_2
        print("Mulitiple is " + str(sum)) 
        
    if operation_sign=='+':
        Addition()
    elif operation_sign=="-":
        Substraction()
    elif operation_sign=='*':
        Multiplication()
    elif operation_sign=='/':
        Division()
    else:
        print('Input correct sign ')   
          
Solution()
