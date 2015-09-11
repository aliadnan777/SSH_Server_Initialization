# SSH_Server_Initialization

### SSH

* One essential tool to master as a system administrator is SSH
* SSH, or Secure Shell, is a protocol used to securely log onto remote systems. It is the most common way to access remote Linux and Unix-like servers, such as VPS instances
* SSH works by connecting a client program to an ssh server

### SSH to connect to a remote system

* The tool on Linux for connecting to a remote system using SSH is called, unsurprisingly, ssh
* `ssh remote_host` ---The remote_host in this example is the IP address or domain name that you are trying to connect to
* This command assumes that your username on the remote system is the same as your username on your local system
* If your username is different on the remote system, you can specify it by using this syntax
* `ssh remote_username@remote_host`
* Once you have connected to the server, you will probably be asked to verify your identity by providing a password



* `ps -aux | grep ssh` ---for checking ssh is enable or not
