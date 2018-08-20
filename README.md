# Log Analysis Project - Udacity

### Full Stack Web Development ND


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

* Python 2 (sudo apt-get install python)
* Psycopg (sudo apt-get install psycopg2)
* Vagrant (You can download from https://www.vagrantup.com/ according to your OS)
* VirtualBox (You can download from https://www.virtualbox.org/ according to your OS)
* Download the data from [here](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip). 
  You will need to unzip this file after downloading it. The file inside is called newsdata.sql.

### Running

1. cd to location where vagrant is present
2. vagrant up
3. add a shared folder on vm
4. copy newsdata.sql in vagrant folder
4. insert guest addition CD image on vm
5. vagrant ssh
6. cd /media/<shared_folder>
7. copy code and database from here to desired location
8. change ownership of folder from root to vagrant 
9. cd folder/vagrant
10. Populate database using dump in shared folder psql -d news -f newsdata.sql
11. python report_tool.py




