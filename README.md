# Password-checker
# To create a password checking basically used in many websites for log in purpose. So in this we are gonna make a code for checking up the password using Python.
username= input('What is your username?')
password= input('What is your password?')
password_length = len(password)
hidden_password = '*' * password_length
print(f'{username},your password,{hidden_password}, is{password_length} letters long')
