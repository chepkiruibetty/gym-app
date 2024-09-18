# GYM WEBSITE

## Author
- Chepkirui Betty

### Description  
This Gym website provides users with an easy-to-navigate interface for booking classes, tracking progress, and staying connected with a community of fitness enthusiasts. Whether you're looking to build strength, improve flexibility, or enhance overall health, Superb Fitness offers a personalized fitness experience that adapts to your unique journey.

### User Story  

* Sign in to the application to start using.  
* Enrol to our classes,one can also view his/her profile
* Choose the package that fits your budget
* Choose the trainer  
* Choose the time you will be available  
  
## deployed link
- https://ancient-falls-03714.herokuapp.com/

  
### Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  

 ```bash 
 https://github.com/chepkiruibetty/gym-app
```
##### Navigate into the folder and install requirements  
 ```bash 
cd seronfitness pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations users
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* Django (Backend)
* HTML/CSS (Frontend)
* JavaScript (Interactive components)
* SQLite (Database)

## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [chepkiruibetty64@gmail.com]  

## license

licensed under[MIT license](license).