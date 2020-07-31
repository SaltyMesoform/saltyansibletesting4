# saltyansibletesting4

This ansible code is intended to allow for updates to an aws hosted mysql database with a specific field set 
This uses an ansible galaxy collection see requirements.txt that should be installed first with the command 
ansible-galaxy collection install -p /Users/Salty/PycharmProjects/saltyansibletesting5/collections/ community.mysql
this wil install to a local folder within the ansible project - omiting the path will install in the root ansible collections folder 

the database user should be configured to REQUIRE SSL and the code will take the pem key from AWS and place on the instance to ensure secure communication

