## Deploying a three node dremio cluster on prem

### some prerequisits 
#### rpm adaption
copy a current dremio rpm into the roles/common/files
e.g. dremio-community-4.2.2-202004211133290458_b550b6fa_1.noarch.rpm

adapt the main.yml in roles/common/tasks to the new file name


### hostname adjustment

adapt the hostnames and IP adresses in hosts file to your enviroment


