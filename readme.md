Utilizes packer to connect to vsphere to make an ubuntu template. Idea was to get a base image for other devops tools to then configure further. 
To use download files and run packer from the folder where you downloaded it after filling in the variables.json with your information and potentially changing the network address in the preseed.
The command to run packer with the variables.json is 'packer build -var-file variables.json ubuntubuildfix.json
Be sure to point to an Ubuntu server ISO and not a live-server ISO
-
