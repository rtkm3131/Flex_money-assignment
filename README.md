# Flexmoney_assignment

This is a complte Yoga application Form with backend intigraded. 

1. Clone the repository into your system

     git clone https://github.com/rtkm3131/Flex_money-assignment

2. Go to this directory

     cd .\Flexmoney_assignment\

3. create virtual environment into your system

     py -m venv myproject

4. Run this command to activate virtual environemnt 

     .\myproject\Scripts\activate

5. From this ( .\myproject\Scripts\activate  )command if are getting error like "execution of scripts is disabled on this system."
     
     then use this link for debugging  
     
     https://stackoverflow.com/questions/4037939/powershell-says-execution-of-scripts-is-disabled-on-this-system

     then after solving issue run .\myproject\Scripts\activate again to  activate virtual environemnt 

6. if your virtual environment is activated then run this command

     cd .\yoga\

7.  Install the requirements for this project use this command

     pip install -r .\requirements.txt
  
8.   apply migrations 

     python .\manage.py makemigrations

     python .\manage.py migrate

9.   Run the server 

     python .\manage.py runserver
  
     you access the website going to this link
  
     http://127.0.0.1:8000/
  
10.  For acessing the backend create superuser

     python manage.py createsuperuser
  
      run the server again

11.   You can access the backend by opening this url

      http://127.0.0.1:8000/admin
  
  
  
 





![9](https://user-images.githubusercontent.com/66213227/207027373-8a57d72a-bacd-4236-ac45-a9900af172d8.png)










