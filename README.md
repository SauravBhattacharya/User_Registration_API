# User_Registration_API

This a user registration api built on Django Rest Framework

![Django_rest_framework](https://user-images.githubusercontent.com/30907911/96553511-e3d8cb00-12d2-11eb-888d-216fe24e229b.png)

-->How to run the project on your computer

Requirements:

          Django

          
          
          Django rest framework
          
          
         
1.Clone the repository

2.pip install all the requirements

3.for fresh start type the following codes on terminal >>

                                                       rm -f db.sqlite3



                                                      rm -r signup/migrations
                                                      
 
4.python manage.py makemigrations signup


5.python manage.py migrate


6.create user: python manage.py createsuperuser


7.runserver: python manage.py runserver 8001  (deafult 8000)




8.Use postman to test the api request: add url to POST method

        
        http://127.0.0.1:8001/api/account/register
        
        
        
        
        
        
 Screen shots:
 
 ![new_reg](https://user-images.githubusercontent.com/30907911/96554574-54ccb280-12d4-11eb-951a-f4cc3617e3ab.PNG)
 
 ![successfull_message](https://user-images.githubusercontent.com/30907911/96554626-69a94600-12d4-11eb-9540-93d5d86c8a4b.PNG)
 
 ![details_stored_in_db](https://user-images.githubusercontent.com/30907911/96555058-edfbc900-12d4-11eb-8a53-b9f7e6b7e80b.PNG)
 
 ![email_validation](https://user-images.githubusercontent.com/30907911/96555323-45019e00-12d5-11eb-93ab-5506898f363a.PNG)


 ![username_validation](https://user-images.githubusercontent.com/30907911/96555329-46cb6180-12d5-11eb-9f86-2bcd3f83af65.PNG)

 
 ![password_validation](https://user-images.githubusercontent.com/30907911/96555327-4632cb00-12d5-11eb-9f81-cd06d2ce8daa.PNG)

        
                  
                  
                  

