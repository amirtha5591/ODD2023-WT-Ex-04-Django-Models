# Ex-04-Django-Models
NAME:AMIRTHA VARSHINI
REFERENCE NUMBER:23000987
Department:CSE
# AIM:
To create django model

# DESIGN PROCEDURE
Django models

# step 1: 
Create django project and app using the following commands django-admin startproject mymodels python manage.py startapp myApp

# step 2: 
create a user_profile models in model.py

![Screenshot 2023-12-30 181107](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/b7ee354d-bc20-466c-b01e-7b8073a1f6e7)


add the models in the admin interface using the code admin.py
![Screenshot 2023-12-30 181120](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/4ed9f9e2-5c45-4c52-ad8e-1350020b88c8)


write the function based view to render the data from the models to the template in views.py
![Screenshot 2023-12-30 181135](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/62d32c5a-2fa9-433a-a0ad-b2820c37b16e)



set up the url path for the templates using urls.py
![Screenshot 2023-12-30 181143](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/0e522a98-4392-42ff-9a5f-327b14da5622)

in settings.py file add the appcreated

# step 3: 
Now do the migrations process to initiate and save the models

python manage.py makemigrations python manage.py migrate create a template as user_profile.html
![Screenshot 2023-12-30 181153](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/056fd9e5-303f-4051-94ff-042824f614d8)

# step4: 
Run the program using the following command

python manage.py runserver 8000 in the admin page you can view the models created and in the user_profile template page you can see the profile page of the user

# Output:
![WhatsApp Image 2023-12-30 at 22 20 21_fab2e7f4](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/2e169653-fea4-4086-9426-fcd6645a0ca4)
![WhatsApp Image 2023-12-30 at 22 19 57_15e09eaf](https://github.com/amirtha5591/ODD2023-WT-Ex-04-Django-Models/assets/145742831/172fe080-d668-4a8e-bfee-ae905844dbfa)





# Result:
Django model was created successfully
