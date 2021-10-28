# CELERY TASK :-
  created a practice purpose project. using celery for sending  email by adding task 
  
* ###### Repository :-
  ```

  ```
  get the project ("demo_celery") directory install some requirements , and some configuration given below 
  and migrate the data :-
  ```
   ./mamage.py makemigrations
   ./manage.py migrate
   ./manage.py runserver
   ```
  open new tab and run the command for running celery
  ```
      celery -A demo_celery worker -l INFO   
  ```

* ###### Requirments :-
    see the `requirements.` txt file 
   ```
    pip intsall -r requirments.txt
   ```   
* ######configuration :- 
  install celery
  ```
      pip install celery
  ```
   For install redis-server  follow the link 
  ```
      https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-redis-on-ubuntu-20-04 
   ```
  
  install RabbitMQ-server
  ```
     sudo apt install rabbitmq-server
  ```
  
  _**User APP**_ :- \
  API :- \ 
* ```
      Method : POST
      localhost:8000/register/
      payload:
   {
         "username": "narendra2",
         "email": "nakushwah@bestpeers.com",
         "first_name": "first",
         "last_name": "last",
         "password": "<password>"
         "password1": "<password1>"

  }
  ``` 
  
