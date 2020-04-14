# key-generator-ssh
Generate keys to your ssh

###### Find your public key ######

1. Open Terminal Console

2. Execute commands below:

 **`find ~/.ssh -name '*.pub' -exec cat {} \;`**
 
 ------
 
 3. If not to locate your keys, execute commands below:
 
 **`ssh-keygen -t rsa -b 4096 -C "your_email@domain.com"`**
 
 Ouput:
 **`Enter file in which to save the key (/home/yourusername/.ssh/id_rsa):`** 

------

Press Enter to accept the default file location and file name.

In the next phase, decide use or not a passphrase to your key.

------
Output:
**`Enter passphrase (empty for no passphrase):`**


If desired to insert a password, typing.

The screen below is displayed.

<a href="https://ibb.co/37wJ00n"><img src="https://i.ibb.co/qdzZRRv/keyoutput.jpg" alt="keyoutput" border="0"></a>

------

To verify your new SSH key pair is generated, type:

**`ls ~/.ssh/id_* `**

------
Output:
**` /home/yourusername/.ssh/id_rsa /home/yourusername/.ssh/id_rsa.pub `**


---------------------------------------------

To copy and login server with your news keys, consulting link below.

https://linuxize.com/post/how-to-set-up-ssh-keys-on-ubuntu-1804/
