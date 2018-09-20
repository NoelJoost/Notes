# SSH - Secure Shell

Remote administration protocol 

Terminal code: ssh {user}@{host}


Symmetric Encryption: One Key
Asymmetric Encryption: public and private keys
-> large Prime number (public)
-> large Prime number (private)

Hashing
Generates unique value of fixed length 

SSH operates on TCP port 22

### Checking & Creating SSH-Key

to check if you got an SSH-key open terminal and enter

`ls -al ~/.ssh`


to create a SSH-key enter in the terminal:

`ssh-keygen -t rsa -b 4096 "E-mail"`

enter than enter a passphrase


### Adding a SSH-Key to the ssh-agent

start the ssg-agent

`èval "$(ssh-agent -s)`

than add the key to the agent.

`ssh-add -K ~~.ssh/id_rsa`

than add it to your account