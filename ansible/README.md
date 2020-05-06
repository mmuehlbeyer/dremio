## Deploying a three node dremio cluster on prem

a short description how to deploy a 3 node dremio cluster with ansible

hosts are split in coordinator and executor roles

dremio01 is used as coordinator host
dremio02 and dremio03 are executor nodes

zookeeper runs on dremio01

### some prerequisits 
#### rpm adaption
copy a current dremio rpm into the roles/common/files e.g. dremio-community-....noarch.rpm

adapt the main.yml in roles/common/tasks to the new file name


#### hostname adjustment

adapt the hostnames and IP adresses in hosts file to your enviroment


