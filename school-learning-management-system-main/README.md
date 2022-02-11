# school-learning-management-system
This school-learning-management system was forked from another repository on Github. Our goal for this project was to find a school learning management system that was not fully complete and improve it from a graphic user interface perspective. The process of this project involved many different methods on how to improve the user interface. First, we created a low and high-fidelity prototype that would be sufficient for a usability test to gain feedback from college students who are already familiar with a school's cloud-based software suite for online and blended classroom learning. Their input helped us complete a set of concrete use cases that gave us ideas on redesigning our application. We then followed different types of principles. One included the principle of recognition; the term comes from Donald Norman's terms of "knowledge in the head" and "knowledge in the world." This process discusses how someone can perform tasks every day and unconsciously combine information stored in their memory with information we locate in the world; Three principles from experience: Visibility- is portrayed as a helpful method to achieve your goals. The principle of visibility suggests that any work you are doing is to achieve a specific purpose; Affordance-We made sure all the use cases for the buttons were obvious. In addition, they are labeled to ensure users can quickly identify what they do. Feedback, The principle of feedback is to communicate the results of any interaction, making it both visible and understandable. 
Installations:
- python 3.7
- pycharm (optional IDE) or any other IDE
- MySql (workbench) (use youtube for installation idea)
- install pip in windows or mac terminal (if needed)
- clone github files from github repository
 
Instructions after installation:
- open manage.py file
- open terminal
- python install -r requirements.txt
- pip install django (if requirements of django installation is not complete)
 
- search for setting.py file in the folders
 
- create database in MySql (workbench) based on the setting.py database name (open setting.py file, go through the code, you will find database section)
- change the setting.py database password to the root password of the MySql (workbench) (root password you kept during installation of MySql)
 
- on terminal in IDE, code: python manage.py migrate
- on terminal in IDE, code: python manage.py runserver
Below is what the school learning management system looks like before any changes were made. 
![HomePage](https://user-images.githubusercontent.com/68065676/121626221-dad17f80-ca96-11eb-954a-5f622fc4829b.png)
![screencapture-127-0-0-1-8000-curriculum-6th-class-6-mathematics-create-2021-06-11-08_25_55](https://user-images.githubusercontent.com/68065676/121626251-e7ee6e80-ca96-11eb-9bf4-690e63bb5a7b.png)
![screencapture-127-0-0-1-8000-curriculum-6th-class-2021-06-11-08_25_20](https://user-images.githubusercontent.com/68065676/121626262-ee7ce600-ca96-11eb-845f-a31d0d673076.png)
![screencapture-127-0-0-1-8000-curriculum-6th-class-2021-06-11-08_27_22](https://user-images.githubusercontent.com/68065676/121626275-f63c8a80-ca96-11eb-94cd-1162908d302d.png)
![screencapture-127-0-0-1-8000-register-2021-06-11-08_23_36](https://user-images.githubusercontent.com/68065676/121626282-f9d01180-ca96-11eb-9b35-4adc471f5363.png)
![screencapture-127-0-0-1-8000-curriculum-6th-class-6-mathematics-2021-06-11-08_25_37](https://user-images.githubusercontent.com/68065676/121626289-fdfc2f00-ca96-11eb-83a7-0a47ae54abb0.png)

After changes:
![chrome_z6vBwBR0Vx](https://user-images.githubusercontent.com/54449540/153532071-d5a52739-72ce-451c-bf6c-ef24472388fb.png)
![chrome_Ts0nCmLMTT](https://user-images.githubusercontent.com/54449540/153532506-afd83851-6002-4763-b024-cebc3aea0d04.png)
![1cCkoi9HGU](https://user-images.githubusercontent.com/54449540/153550919-58e1f202-1b6e-4adb-8a6c-223e57246533.png)![chrome_UPu9hYetQQ](https://user-images.githubusercontent.com/54449540/153533636-9ed7fe19-f109-4250-bc54-a85bf2f58392.png)

