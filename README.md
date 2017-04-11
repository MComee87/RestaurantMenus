For this project you to work properly you need a unix-style terminal, virtualbox and vagrant installed on your machine.

From the terminal, run:

git clone https://github.com/MComee87/RestaurantMenus-db


Now cd into the RestaurantMenues-db directory and type vagrant up to launch the virtual machine.
once this is finished type vagrant ssh to connect to your virtual machine.

to initialize the database type python database_setup.py

topopulate the database type python lotsofmenus.py 

type python project.py to start the web server and visit http://localhost:5000 to  view Menu App.