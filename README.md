# Generating-keys-for-SSH
ssh-keygen                  // "dont copy this"-comments:it is used for generating the public and private keys of an user
(it will display ur public key is saved in home/username/.ssh/id_rsa.pub)
cat home/username/rsa_key.pub                //comments:it will open the public key
// comment: copy that public key and store it in "authorized_keys"

vi ~/.ssh/authorized_keys       //comments: it will open the file and paste the copied key previuosly generated one
ssh-copy-id root@servername      //server name can be ip address too
// it will get copied so it means ur public key will get resided into the server so u dont need to use ur password again and again
ssh root@servername            //it will get direct access instead of typing the pswd and getting the login



------THANK YOU------------
