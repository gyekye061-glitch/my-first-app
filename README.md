student = {  
    "Name": "Emmanuel",
    "age": 21,
    "course": "mathematics"
}  #dict
print(student["Name"])
print(student["age"])
print(student["course"])
boss = ("Emmanuel", 21, "mathematics") #tuple
print(boss[1])
  #type
person = "Ama"
print(type(person))
isinstance(person, (int, float)) #False
name = 'Alice'
print(name)
print(type(name))
#ISINSTANCE FUNCTION
is_student = True
print(is_student)
print(isinstance(is_student, bool))
#STRING
quote = "She said, \"HELLO\""
print(quote)
my_str = "Hello World"   #LEN function
print(len(my_str))
you = 'AMA'  #STRING CONCATENATION
me = 'GYEKYE'
print(you+' '+me)
am = 'Regina'  #STRING INTERPOLATION
an = 21
am_and_an = F'My girlfriend, {am} is {an} years old'
print(am_and_an)
her = "AMA"     # CHANGE ALPHABELTS
lowercase_her = her.lower()
print(lowercase_her)
first_name = 'John'
last_name = 'Doe'
full_name = first_name + ' ' + last_name
address = '123 Main Street'
address += ', Apartment 4B'
employee_age = 28
employee_info = full_name + ' is ' + str(employee_age) + ' years old'
print(employee_info)
experience_years = 5
experience_info = 'Experience: ' + str(experience_years) + ' years'
print(experience_info)
position = 'Data Analyst'
salary = 75000
employee_card = f'Employee: {full_name} | Age: {employee_age} | Position: {position} | Salary: ${salary}'
print(employee_card)
employee_code = 'DEV-2026-JD-001'
department = employee_code[0:3]
print(department)

