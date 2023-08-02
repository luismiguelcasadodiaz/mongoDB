# mongoDB
The aim of this exercise is learn a little bit about this NOSQL database.

The leasson is a BOOK CRUD (Create, read, update, delete) exercise.

## Create a free cloud instance with Atlas

I did it in a data center from GCP in Belgium. It is a shared vCPU & RAM M0 sandbox with an storage space of 512 MB. 
It uses a MongoDb6.0 wiht no Backup policy.

This free account offers some sample data to start playing wiht (9 database wiht 23 collections)

![image](https://github.com/luismiguelcasadodiaz/mongoDB/assets/19540140/e2d0a4c3-adac-4539-98da-73a2b9bdb3c4)

I installed mongoDB Compass to see data from my notebook. Online Atlas web Page will provide URL to connect.
During the instance creation i need to enter my IP. Atlas will register it to allow my access form my computer.

## Create a virtual environment
and install this packages 'fastapi[all]' 'pymongo[srv]' python-dotenv

## Create Book Entity
From Pydantic BaseModel i add some entity attributes such us id, title, authos and synopis, all of type str.



