
 az vm create --name neemyvm --resource-group rgroup2 --image Ubuntu2204 --vnet-name testclivnet --subnet examplesubnet /
 --generate-ssh-keys --output json --verbose --admin-username lenovot430



 Delete RG

 az group delete --name rgroup2
