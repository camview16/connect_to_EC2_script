# Custom binary script to connect to AWS EC2 instance

This script will allow you to replace the traditional "ssh -i pem_file user_name@host_name" command with user defined binary script.

The script has been tested on Linux Ubuntu 18.04.3 LTS (GNU bash, version 4.4.20(1)-release)

How to use :

1> Run the script by executing the following command :

	bash create_ssh_script 
	OR
	./create_ssh_script

2> Follow the instructions to provide the necessary details. 

3> Once complete, a binary script will be created in "/usr/local/bin/" directory with the name provided.

4> Execute the binary script to connect to the EC2 instance. 
