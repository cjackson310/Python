```python
print("Hello, Welcome to the Geography Quiz")
score = 0
question_no = 0
playing = input('Do you want to play? ').lower()
if playing == "yes":
    question_no +=1
    ques = input(f'\n{question_no}. What is the largest continent? ')
    
    if ques == 'Asia':
        print('Correct! You got 1 point.')
        score +=1
                     
    
    else:
        print('Incorrect')
        print(f'The correct answer is --> Asia. ')
        
        
#------1
    question_no +=1
    ques = input(f'\n{question_no}. Which country has the most natural lakes? ')
    
    if ques == 'Canada':
        print(f'Correct! You got 1 point.')
        score +=1
        
    else:
        print('Incorrect')
        print(f'The correct answer is --> Canada. ')
        
        
#------2
    question_no +=1
    ques = input(f'\n{question_no}. What is the smallest country in the world? ')
    
    if ques == 'Vatican City':
        print('Correct! You got 1 point.')
        score +=1
        
    else:
        print('Incorrect')
        print(f'The correct answer is --> Vatican City. ')
        
        
#------3
    question_no +=1
    ques = input(f'\n{question_no}. Which Central American country translates to "The Savior" in English? ')
    
    if ques == 'El Salvador':
        print('Correct! You got 1 point.')
        score +=1
        
    else:
        print("Incorrect")
        print(f'The correct answer is --> El Salvador. ')
        
        
#------4
    question_no +=1
    ques = input(f'\n{question_no}. What is the largest country in Africa? ')
    
    if ques == 'Algeria':
        print('Correct! You got 1 point.')
        score +=1
    
    else:
        print('Incorrect')
        print(f'The correct answer is --> Algeria. ')
        
#------5



else:
    print("Thank you! You are done with this quiz.")
    quit()
    
print(f'\nnumber of questions are {question_no}')   
print(f'Your score is {score}')
try:
    percentage = (score *100/question_no)
except ZeroDivisionError:
    print('0% of questions are correct')

print(f'{percentage}% are correct')
        
```

    Hello, Welcome to the Geography Quiz
    Do you want to play? yes
    
    1. What is the largest continent? Asia
    Correct! You got 1 point.
    
    2. Which country has the most natural lakes? Canada
    Correct! You got 1 point.
    
    3. What is the smallest country in the world? Vatican City
    Correct! You got 1 point.
    
    4. Which Central American country translates to "The Savior" in English? El Salvador
    Correct! You got 1 point.
    
    5. What is the largest country in Africa? Nigeria
    Incorrect
    The correct answer is --> Algeria. 
    
    number of questions are 5
    Your score is 4
    80.0% are correct



