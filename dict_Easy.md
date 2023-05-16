# Initialize a dictionary "emp_info" with below details
# In - emp_info['Tom']
# Out - {'email':'tom_latham019@gmail.com', 'Phone': +1987654321, 'City': 'Californ

a = ['Name','email','Phone','City']
b = ['Tom','tom_latham019@gmail.com', '+1987654321' ,'California']
emp_info = dict(zip(a,b))
emp_info
# In - emp_info['Kathy']
# Out - {'email':'kathy_abram897@gmail.com', 'Phone': +1887654321, 'City': 'New Yor
c = ['Name','email','Phone','City']
d = ['Kathy','kathy_abram897@gmail.com', '+1887654321' ,'New York']
emp_info1 = dict(zip(c,d))
emp_info1
