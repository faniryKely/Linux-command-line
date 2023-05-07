Now you are in bandit6
follow this command to find the bandit7 password 
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
bandit6@bandit:~$ 

here is bandit6 password z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S