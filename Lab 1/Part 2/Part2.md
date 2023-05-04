## Create the inventory file
## Put the IP of host 1 in the inventory file
## Use the inventory file path in your ad-hoc command instead of using the IP hard-coded
## Example:
ansible all -i inventory --private-key ~/.ssh/devops -u ubuntu -m ping
![Screenshot from 2023-05-01 18-54-21](https://user-images.githubusercontent.com/71722372/235484641-956f06e3-6509-435c-9d4f-ed668134e58f.png)
