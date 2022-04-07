### Authenticating on multiple GitHub accounts using SSH

# video explanation link 
https://www.youtube.com/watch?v=N2hMGEeYR7c

# terminal commands 
step 1 enter to the ssh folder 
cd .shh

step 2 check content of folder
ls 

step 3 generate ssh key
shh-keygen

step 4 grab a content of key 
cat id_rsa.pub

step 5 add key to github repo

step 6 crate config file
notepad config 

config file should not to be txt
mv config.txt config

step 7 generate second key 
shh-keygen -f name_id_rsa

step 8 grab a content of second key 
cat name_rsa.pub

step 9 update config file
