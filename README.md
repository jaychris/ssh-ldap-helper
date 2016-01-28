# ssh-ldap-helper

a simple bash script cadged and updated from around the internet (other versions didn't work quite right).  

Suitable for use with OpenSSH public key authentication against LDAP; should work with any distro (Ubuntu, Debian, CentOS, etc...) though RH flavors already have a working binary for this in openssh-ldap package.

For this to work, you'll have to have an existing schema in LDAP that provides sshPublicKey and a key uploaded.  Lots of tutorials out there for that...
