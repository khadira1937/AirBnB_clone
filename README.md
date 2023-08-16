# 0x00. AirBnB clone - The console

Group project created Using python language programming ,during Full Stack Software Engineering studies at **ALX AFRICA SE School**.

## 0x00.Table of contents



## 0x01 Introduction
building Airbnb website using python.

## 0x03 Installation

```bash
git clone https://github.com/RedaRahmani/AirBnB_clone
```
### Execution

to execute Airbnb Clone you need to run this command:
In interactive mode

```bash
 ./console.py
```

in Non-interactive mode:

```bash
$ echo "help" | ./console.py
```
## 0x04 Testing
All Test file are defined in `Tests` Folder

### run test in interactive mode
```bash
echo "python3 -m unittest discover tests" | bash
```
### run test in non-interactive mode

```bash
python3 -m unittest discover tests
```

## 0x05 Usage
To start airbnb clone you need to run this command :
```bash
$ ./console.py
(hbnb)
```
Run help command to see all available command:
```bash
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
```

Run the command quit to exit the console :

```bash
(hbnb) quit
$
```

### Commands

* Create:
create command let you to create a new instance with a unique id , and the id he will display after runing this command:
```bash
(hbnb) create BaseModel
42b01839-0a02-4d94-9c24-2fa28eccf82c
(hbnb)
```


* Show
show command let you to display all informations about an instance :
```bash
(HBNB)show BaseModel 42b01839-0a02-4d94-9c24-2fa28eccf82c
[BaseModel] (42b01839-0a02-4d94-9c24-2fa28eccf82c) {'id': '42b01839-0a02-4d94-9c24-2fa28eccf82c', 'created_at': datetime.datetime(2023, 8, 13, 19, 19, 39, 379732), 'updated_at': datetime.datetime(2023, 8, 13, 19, 19, 39, 379732)}
(HBNB)
```

* Destroy
Destory command let you to remove an instance from the storage :
you need to use destory command with the name of class and the id of the instance.

```bash
(HBNB)create User
4fb82e29-9101-4d42-8b9a-91e361e9fe2e
(HBNB)destroy User 4fb82e29-9101-4d42-8b9a-91e361e9fe2e 
(HBNB)show User 4fb82e29-9101-4d42-8b9a-91e361e9fe2e
** no instance found **
(HBNB)
``` 

* all

all Command let you to display all instances in string representation:

```bash
(hbnb) all User
["[User] (d5590322-691a-4201-8729-a36ab0b44c59) {'id': 'd5590322-691a-4201-8729-a36ab0b44c59', 'created_at': datetime.datetime(2023, 8, 13, 19, 44, 33, 803579), 'updated_at': datetime.datetime(2023, 8, 13, 19, 44, 33, 803579)}",
```


* count

count command let you to display the number of instance of a class given:

```bash
(HBNB)count User
104   
(HBNB)
```

* update

update command let you to update an instance :
```bash
(HBNB)create User
e93078e7-e348-4978-ad3c-743ccd7b2c98
(HBNB)update User e93078e7-e348-4978-ad3c-743ccd7b2c98 email "khadira-rahmani@gmail.com" 
(HBNB)show User e93078e7-e348-4978-ad3c-743ccd7b2c98
[User] (e93078e7-e348-4978-ad3c-743ccd7b2c98) {'id': 'e93078e7-e348-4978-ad3c-743ccd7b2c98', 'created_at': datetime.datetime(2023, 8, 13, 22, 29, 50, 636756), 'updated_at': datetime.datetime(2023, 8, 13, 22, 29, 50, 636756), 'email': '"khadira-rahmani@gmail.com"'}
(HBNB)

```

## 0x06 Authors

*RAHMANI MOHAMED REDA <mohamedreda.rahmani20@ump.ac.ma>
*KHADIRA OUSSAMA <okhadira@gmail.com>







